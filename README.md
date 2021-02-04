# Discord-Presence-RPC
Discord Rick Presence


> // Code // 
  
const RPC = require("discord-rpc");  
const rpc = new RPC.Client({  
    transport: "ipc"  
})  
rpc.on("ready", () => {  
    rpc.setActivity({  
        details: "state_name",    
        state: "state_name",  
        startTimestamp: new Date(),  
        largeImageKey: "image_name",  
        largeImageText: "image_text",  
    })  
    console.log("Tudo Funcionando! by.const")  
})  

rpc.login({  
    clientId: "client_id"  
})  
  
> //  npm i discord_rpc


> // by const // 

