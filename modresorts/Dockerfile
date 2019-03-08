FROM ibmcom/websphere-traditional
COPY modresorts-1.0.war /work/config/modresorts-1.0.war
COPY install_app.py /work/config/install_app.py
COPY was-config.props /work/config/was-config.props
RUN /work/configure.sh
