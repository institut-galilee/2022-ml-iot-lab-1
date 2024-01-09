# 2024-ml-iot-lab-1

The following activities will be useful for the final project. The various components that you will build throughout this lab will be included in the NetworkManager and the Mobile application of the project (more information about these parts later).

## Activity one
* Setting up a local network using you PC as a hotspot (access point);
* Launch the local network either manually or programmatically, i.e., preferably via a Python program. You have to search for platform-specific solutions.

![hotspot-client](https://user-images.githubusercontent.com/8298445/144478047-2818168d-828d-4dd1-84c4-48ac4c8ad5e0.png)


## Activity two
* Take a look at https://grpc.io/docs/what-is-grpc/ to get an overview of what is meant with remote procedure calls (RPC)
* Define a remote procedure call protocol with `gRPC`

## Activity three
* Define a Python program which will run on the PC and make use of the RPC protocol to serve remote procedure calls
* https://grpc.io/docs/languages/python/quickstart/

## Activity four
* Define a Kotlin program which will run on an Android device and make remote procedure calls to the Python server above
* https://grpc.io/docs/languages/kotlin/quickstart/


## Activity five
* Use the RPC protocol defined above to perform communications between a Kotlin program (running on the mobile device) and the Python server (running on a PC)

![rpc_Kotlin-to-Python](https://user-images.githubusercontent.com/8298445/144479920-d239c3bb-4667-4e68-83c0-624bb0b986d6.png)



## Activity four
* Now we ask you to go the way around, i.e., a Python client (running on a PC) connects to a Kotlin serving remote procedure calls on an Android device;
* Setting up a server on your mobile device (Android/Kotlin). Hint: make use of `io.grpc.netty.shaded.io.grpc.netty.NettyServerBuilder`;
* Implement the RPC protocol in Android to handle the remote procedure calls

![rpc_Python-to-Kotlin](https://user-images.githubusercontent.com/8298445/144479951-731a0a52-1723-4c85-bec9-2776e619baa0.png)


## Activity six
* Define a network manager that listens to the incoming connections to the access point and outputs the assigned local IP address.

## Activity seven
* Create an Android activity that reads the phone's camera stream

## Activity eight
* Create an Android activity that reads the phone's motion sensors streams
