# sam-fastapi-guide
- sam-fastapi-guide is a template for building a serverless API with FastAPI and AWS SAM.

## Steps
```bash
- $ sam build (if python 3.9 or "sam build --debug --use-container" (over python 3.10)
- $ sam deploy --guided
```

## Github action
The "workflow.txt" is a workflow for this template.
If you want to use the Github Actions, check the below.

1. Create a .github folder in the root of your project.
2. Create a workflows folder inside the .github folder.
3. Create a main.yml file inside the workflows folder.
4. Copy the contents of the workflow file from the template into the main.yml file.
5. Check the key names in the workflow file and make sure they match the names of your AWS resources.

## Reference
- https://vallyscode.github.io/posts/aws-sam-basics/
- https://velog.io/@insutance/simple-deploy-with-fastapi-mangum-lambda-sam

