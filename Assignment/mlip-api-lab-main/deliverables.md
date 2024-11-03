## Deliverables
1. [/] Create an account and connect to the Azure Vision API
2. [/] Explain to the TA why hard-coding credentials is a bad idea. Commit your code to GitHub without committing your credentials.

Ans: 

Hard-coding credentials will allow unauthorized users to access sensitive information or the api key easily. It is also harder to rotate credentials if it is hard-coded as the code need to be modified to update.

3. [/] Run the API endpoint with the starter code and demonstrate that it works with an example invocation (e.g., using curl).

Ans: 

curl -X GET "http://localhost:3000/api/v1/analysis/" -H "Content-Type: application/json" -d "{\"uri\": \"https://upload.wikimedia.org/wikipedia/commons/3/3a/Cat03.jpg\"}"

curl -X GET "http://localhost:3000/api/v1/analysis/" -H "Content-Type: application/json" -d "{\"uri\": \"D:/ProgrammingProjects/VSCode/Prac_AI/Assignment/mlip-api-lab-main/kitty.jpg\"}"