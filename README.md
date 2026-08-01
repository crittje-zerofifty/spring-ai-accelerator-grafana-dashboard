# spring-ai-accelerator-grafana-dashboard
Contains a json to explore OpenTelemetry, combining metrics and traces in Grafana dashboard.

Can be applied to the **Spring AI Accelerator** application: https://github.com/crittje-zerofifty/spring-ai-accelerator

Run the **Spring AI Accelerator** app with profiles `history,ollama` and run a GET request like:

`http://localhost:8080/chat?prompt=What is the weather today?&chatId=2`

run it a few times, change the promp. And the dashboard will have information. The chatId can be used to filter per chat on the monitoring dashboard.

