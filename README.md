# conda

docker build -t conda:1.0 .

docker run conda:1.0 conda -V

docker run -it conda:1.0 conda bash

