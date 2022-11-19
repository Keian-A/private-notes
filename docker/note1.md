# What is docker?

A platform for building, running, and shipping applications in a consistant manner.

Reasons:
1. One or more files are missing
1. Software version mismatch
1. Different configuration settings

We can "package" our application with specific versions of those packages.

To run an application on a new system, use the following command:

```bash
docker-compose up
```

We can remove an application and all it's dependancies in one go with the following command:

```bash
docker-compose down --rmi all
```

This is used to clean up our machine from the no-longer-used applications.