# courior The courier package is designed to provide a method of quick unstructured logging to a separate server instance (language agnostic). This is especially useful in two contexts

1) You want to keep a record of what is going on in your main process beyond printing to the console

and more usefully

2) You are working in a parallelizable context and want to send messages out from a worker thread. As messages do not bubble up

The entire construction/teardown of the machinery takes less than 3 ms, making it very low overhead
