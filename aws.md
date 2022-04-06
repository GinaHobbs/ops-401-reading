# AWS Architecture Blog - Compute Abstractions on AWS: A Visual Story

When using AWS, the service is delineated between the consumer and the provider. The provider will be in charge of fixing and maintaining certain issues on their side, and the consumer will be in charge of fixing and maintaining issues on their side. Abstraction allows the consumer to implement their own OS and middleware on AWS systems. Two examples are EC2 and Lightsail, each which allow the consumer to host their systems or application in the cloud without worrying about the hardware it's running on. Containers, such as those created with Docker, allow the consumer to virtualize an OS so they can run separated applications with different and often incompatible dependencies.