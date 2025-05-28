# Lab8-Starter

Vincent Nguyen\

Graceful degradation is starting from the features and gracefull removing features if browser capabilities decline. Service workers support graceful degradation by allowing your program to function even when connectivity is lost. Service workers are installed in the browser and run separately from the web page itself. They can continue to help with loading resouces(HTML, CSS, JS), intercept netwrok requests, and support cache content offline. So even if the feature fails from network issues, service workers will be there to help support your app by allowing it to gracefully fall back.