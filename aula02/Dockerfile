FROM postgres

# informa ao postgres que o arquivo de senha esta em /var/cedro/secret
ENV POSTGRES_PASSWORD_FILE=/var/cedro/secret

#copia o arquivo com a senha para /var/cedro/secret para que o postgres possa ler
COPY secret ${POSTGRES_PASSWORD_FILE}