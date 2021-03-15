
### Code to Help me learn on how to GO and on how to blockchain

[Read](https://medium.com/@mycoralhealth/code-your-own-blockchain-in-less-than-200-lines-of-go-e296282bcffc) blog post to see a walkthrough of the code.

### Deployment steps:
-  Add ENVS to the example file ` .env`
- `go run main.go`
- open a web browser and visit `http://localhost:8080/`
- to write new blocks, send a `POST` request (`curl -X POST -H "Content-Type: application/json"  -d '{"BPM": 50}' http://127.0.0.1:8080`) to `http://localhost:8080/` with a JSON payload with `BPM` as the key and an integer as the value. For example:
```
{"BPM":50}
```
- Send as many requests as you like and refresh your browser to see your blocks grow! Use your actual heart rate (Beats Per Minute) to track it over time.




