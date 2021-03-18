
IMPORT github.com/earthly/hello-world:main

COPY_CAT:
  COMMAND
  COPY message.txt ./
  RUN cat message.txt

TOUCH:
  COMMAND
  ARG file=touched
  RUN touch $file

FROM_HELLO_WORLD:
  COMMAND
  FROM hello-world+hello
