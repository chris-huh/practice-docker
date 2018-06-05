Docker Container tutorial from official Docker Documentation
@ https://docs.docker.com/get-started/part2

# To build the app
```docker build -t friendlyhello .```

# To run the app (-p for port piping, -d for detached mode)
```docker run -p 4000:80 friendlyhello```

# now app is accessible at localhost:4000
