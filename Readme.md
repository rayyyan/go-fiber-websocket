### this is a setup template for Go Fiber with websocket

- run the project
- open the browser
- in the console establish new websocket connection something like => `let ws =new WebSocket("ws://localhost:3000/ws/<User_Id>")`
- define a message object:

* let message ={
  data:"hello",
  from:"1235",
  event:"Create_order",
  to:"1234"
  }

- ws.send(JSON.stringify(message))
- and voila check the console
