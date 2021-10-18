
  # Features of NodeJS

    18 October 2021 08:00

  ## Features of NodeJS:

1. Asynchronous event driven I/O help in concurrent request handling.
      
    Eg:

  ```js
  var fs = require('fs');
  fs.readFile("Sample.txt",function(error,data)
  {
  console.log("Reading Data completed");
  });
  ```

-   The above code snippet looks at reading a file called Sample.txt. In
      other programming languages, the next line of processing would
      only happen once the entire file is read.

-   But in the case of Node.js the important fraction of code to notice
      is the declaration of the function ('function(error,data)'). This
      is known as a callback function.

-   So what happens here is that the file reading operation will start
      in the background. And other processing can happen simultaneously
      while the file is being read. Once the file read operation is
      completed, this anonymous function will be called and the text
      "Reading Data completed" will be written to the console log.

----------------

1. Node uses the V8 JavaScript Runtime engine, the one which is used by
      Google Chrome. Node has a wrapper over the JavaScript engine which
      makes the runtime engine much faster and hence processing of
      requests within Node also become faster.

2.  Handling of concurrent requests – Another key functionality of Node
      is the ability to handle concurrent connections with a very
      minimal overhead on a single process.

3.  The Node.js library used JavaScript – This is another important
      aspect of development in Node.js. A major part of the development
      community are already well versed in javascript, and hence,
      development in Node.js becomes easier for a developer who knows
      javascript.

  ## Who uses Node.js?

• Paypal – A lot of sites within Paypal have also started the transition onto Node.js. 

  • LinkedIn - LinkedIn is using Node.js to power their Mobile Servers, which powers the iPhone, Android, and Mobile Web products. 

  • Mozilla has implemented Node.js to support browser APIs which has half a billion installs.

• Ebay hosts their HTTP API service in NodeJS

  [<-Previous Page](https://github.com/kanitmann/Learn_With_Me)                                        
  
  [Next page ->]()