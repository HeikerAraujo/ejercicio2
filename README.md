docker pull nicopaez/pingapp:3.0.0

docker run -P -d nicopaez/pingapp:3.0.0

docker tag nicopaez/pingapp:3.0.0 hkaraujo/ejercicio2:1.0.0

docker push hkaraujo/ejercicio2:1.0.0
