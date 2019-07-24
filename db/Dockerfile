FROM mysql:5.7.22
EXPOSE 3306
COPY ./DockerToAWSWithDotNet/db/migrations/ /home/database/
COPY ./DockerToAWSWithDotNet/db/dataset/ /home/database/
COPY ./DockerToAWSWithDotNet/ci/init_database.sh /docker-entrypoint-initdb.d/init_database.sh