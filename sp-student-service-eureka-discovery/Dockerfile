FROM java:8
RUN mkdir /var/tmp/studentservice
COPY ./build /var/tmp/studentservice/
RUN ls /var/tmp/studentservice/
WORKDIR /var/tmp/studentservice
EXPOSE 8090
CMD ["./bootScripts//student_service_eureka"]
