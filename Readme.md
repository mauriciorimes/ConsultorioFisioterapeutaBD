Comandos SQl com o seguinte esquema relacional:

Paciente(codigo, nome*, e-mail, celular*)

Fisioterapeuta(codigo, nome*, numero_conselho*,e-mail)

TipoAtendimento(codigo,descricao)

Atendimento(codigo, data*, hora*,paciente_codigo*,fisio_codigo*,TpAtendimento_codigo*,total*)

paciente_codigo referencia paciente

fisio_codigo referencia fisioterapeuta

TpAtendimento_codigo referencia TipoAtendimento