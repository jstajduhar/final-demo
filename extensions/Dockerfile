FROM registry.access.redhat.com/jboss-datavirt-6/datavirt63-openshift

LABEL Name="final-demo" \
      Version="latest"

COPY files /extensions/
#COPY modules /extensions/modules/
#COPY flight-data.txt /extensions/files/data/
COPY install.sh /extensions/
COPY install.properties /extensions/

COPY files/data/flight-data.txt /home/jboss/source/extensions/extras/data/

