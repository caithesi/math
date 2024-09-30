# Math-for-Programmers
Source code for the book, Math for Programmers

Up-to-date on GitHub at https://github.com/orlandpm/Math-for-Programmers

To run with docker:
    - docker build -t image-name .
    - docker run --rm -p 8889:8888 -v "$(pwd):/home/jovyan/work" image-name start-notebook.py --NotebookApp.token='my-token'
    where -p 8889:8888: Maps port 8889 from the host to port 8888 on the container.
    start-notebook.py --NotebookApp.token='my-token': Sets an access token rather than using a random token.

    - for more details, read https://docs.docker.com/guides/use-case/jupyter/
