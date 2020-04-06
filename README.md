# Serverless v1.65 role naming breaking change

Deploy function using serverless 1.64:

    npx sls deploy -v

The function can be executed as follows:

    npx sls invoke -f hello -l

Install Serverless 1.65:

    npm i -D serverless@1.65.0


Deploy function again:

    npx sls deploy -v
