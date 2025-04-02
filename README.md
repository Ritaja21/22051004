# Average Calculator API

This is an Express.js API that fetches numbers from different third-party endpoints, maintains a sliding window of the last 10 unique numbers, and calculates their average.

## Features
- Fetch numbers from different third-party APIs.
- Maintain a sliding window of up to 10 numbers.
- Compute and return the average of stored numbers.
- Implement error handling for API failures.
- Secure API calls with authorization.

## Technologies Used
- **Node.js** with **Express.js**
- **Axios** for HTTP requests


## Testing in Postman
1. Open **Postman**.
2. Set **GET** request to `http://localhost:9876/numbers/p`.
3. In **Headers**, add:
   ```
   Key: Authorization
   Value: Bearer your_generated_access_token
   ```
4. Click **Send** and verify the response.





