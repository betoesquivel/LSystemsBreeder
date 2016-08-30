# LSystemsBreeder
Turtle-rendered LSystems genetic generator application, uses genetic algorithms to generate new LSystems, using user ranking feedback as the fitness function for the individuals. Built using AWS Lambdas, S3, and DynamoDB. Main issues along the way: 1) How do you run libraries like node-canvas, which use native libraries, on AWS Lambdas? Solution was to follow: WebSeed/node-canvas-aws-lambda-example and avoid using Node 4.3 as a runtime. System initially built for HackMTY, however, since we weren't allowed to participate from outside of Mexico, we just ended up building it at our own pace.
