docker build -f DockerfileOT -t example-ot:fixPlotting .


docker tag b0c65fb6301d johnalison/example-ot:fixPlotting
docker push johnalison/example-ot