Caso retorne esse erro:
QueryFailedError: function uuid_generate_v4() does not exist ao executar o comando yarn typeorm migrate:run
rode o seguinte comando no banco de dados postgres:
CREATE EXTENSION IF NOT EXISTS "uuid-ossp";
