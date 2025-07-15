# Restituicao
Me foi demandado um projeto com o seguinte cenário:
Um arquivo Excel para alimentação do próprio gestor de forma que consiga conectar um painel a ele, mantendo tudo atualizado.
Com esse cenário escolhi o seguinte, um arquivo Excel dentro do Dropbox, ferramenta de armazenamento em nuvem que usamos dentro da empresa, conectado por link ao PowerBI, assim sempre que for alterado algo dentro da planilha e salvada ira refletir no painel.
Para garantir que o link na web do painel sempre esteja atualizado, desenvolvi uma RPA com Selenium para  automatizar o processo de atualização do dataset.
Tudo isso automatizei e criei uma rotina com o agendador de tarefas rodando a cada 2 minutos, alcançando todas necessidades e propostas de mercado que me foram passadas.
Link do painel (dados fictícios): https://app.powerbi.com/view?r=eyJrIjoiNGIzMjc0YmYtZmFlMS00NmI4LTk2YWUtMmEwZTUzMWMyYTc3IiwidCI6IjdlNWQzNzVhLWYyNDMtNDQ3NS1iNmJmLTQzMTI5OWYwYWFhOSJ9
