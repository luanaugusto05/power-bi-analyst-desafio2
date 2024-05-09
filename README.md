# Desafio - Processando e transformando dados com Power BI <img src="https://static-00.iconduck.com/assets.00/power-bi-icon-384x512-bujnuaon.png" width="30" height="40">

- Após fazer uma análise rápida para verificar se não há alguma redundância nos dados, foi realizado a mesclagem das tabelas employee e departament, preservando os dados da tabela employee e a coluna de junção sendo a matrícula do gerente.
![image](https://github.com/luanaugusto05/power-bi-analyst-desafio2/assets/113543581/26b5af8b-babb-4eb4-b693-17e270034523)

- Logo após, foi realizada a separação da coluna Adress em Street, Number, City e State, também foi transformada a coluna salário para número decimal fixo.
![image](https://github.com/luanaugusto05/power-bi-analyst-desafio2/assets/113543581/2f7d51ab-ca0d-40ba-8e65-ad0dd30bd232)

- Em seguida, as colunas da tabela employee-departament foram reordenadas, foi realizada a junção do nome a fim de colocar o nome completo em uma única observação, também foi ralizada uma mesclagem para criar uma coluna com o nome do gerente de cada colaborador.
![image](https://github.com/luanaugusto05/power-bi-analyst-desafio2/assets/113543581/ce2fcaea-58cd-4d96-97dd-88499e868198)

- Foi realizada a contagem de colaboradores por gerente, percebe-se que um colaborador não possui gerente, pois provalvelmente deve ser o gerente-chefe.
![image](https://github.com/luanaugusto05/power-bi-analyst-desafio2/assets/113543581/1fc8a5e6-debd-4cbd-9a4c-8a396a3284aa)

- Foi realizada a mesclagem da tabela departamento e localização.
![image](https://github.com/luanaugusto05/power-bi-analyst-desafio2/assets/113543581/33c8dd64-23f9-403e-be22-d3c05b6f0949)

- Foi realizado o agrupamento de projeto, sendo o valor retornado a quantidade de horas total por cada projeto.
![image](https://github.com/luanaugusto05/power-bi-analyst-desafio2/assets/113543581/496a8094-4e4b-4985-a3bf-18a7cce0c971)

- No exemplo a seguir, devemos utilizar a ferramenta mesclar e não a atribuir, pos necessita-se que o colaborador esteja conectado ao seu respectivo gerente. Ao usarmos a ferramenta atribuir, não garantimos que isso ocorrerá.
![image](https://github.com/luanaugusto05/power-bi-analyst-desafio2/assets/113543581/d48ccc20-4f6b-47f5-8415-d3f0a122021a)
