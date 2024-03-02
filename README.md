# Random Indian Name Generator API

This API provides endpoints to generate random Indian names.

## Access the Endpoints:

### Base Endpoint:
`https://random-indian-name-generator.vercel.app`

---

- **Random Name Object Endpoint:**
  - **Endpoint:** [/api/random_name](https://random-indian-name-generator.vercel.app/api/random_name)

  - **Description:** Generates a random name object with separate keys for first name, father name, and last name.
-
  - **Example Output:**
    ```json
    {
      "firstName": "Nikishing",
      "fatherName": "Prahalasang",
      "lastName": "Pillai"
    }
    ```

- **Random Full Name Endpoint:**
  - **Endpoint :** [/api/full_name](https://random-indian-name-generator.vercel.app/api/full_name)
-
  - **Description:** Generates a random full name string.

  - **Example Output:**
    ```json
    {
      "fullName": "Sagunsingh Chander Basu"
    }
    ```

- **Random Names Array Endpoint:**
  - **Endpoint:** `/api/random_names/:count`
  - [/api/random_names/:count](https://random-indian-name-generator.vercel.app/api/random_names/5)

  - **Description:** Generates an array of random name objects. Maximum count allowed is 100.

  - **Example Output:** Accessing `/api/random_names/3` could return:
    ```json
    [
      {
        "firstName": "RandomFirst1",
        "fatherName": "RandomFather1",
        "lastName": "RandomLast1"
      },
      {
        "firstName": "RandomFirst2",
        "fatherName": "RandomFather2",
        "lastName": "RandomLast2"
      },
      {
        "firstName": "RandomFirst3",
        "fatherName": "RandomFather3",
        "lastName": "RandomLast3"
      }
    ]
    ```
