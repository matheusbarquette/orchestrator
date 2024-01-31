
## Orquestração de tarefas em python

Orquestrar scripts desenvolvidos em python, projeto tem como principal objetivo gerar tarefas e fazer sua devida gestão.


## Rascunho do projeto

![App Screenshot](https://github.com/matheusbarquette/orchestrator/blob/main/assets/fluxo.png?raw=true)

## Demo

![Logo](https://github.com/matheusbarquette/orchestrator/blob/main/assets/demo.gif?raw=true)

## Stack utilizada

<p align="left"> 
    <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/>
    </a>
    <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> 
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/>
    </a> 
    <a href="https://www.python.org" target="_blank" rel="noreferrer"> 
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/>
    </a> 
    <a href="https://www.rabbitmq.com" target="_blank" rel="noreferrer"> 
        <img src="https://www.vectorlogo.zone/logos/rabbitmq/rabbitmq-icon.svg" alt="rabbitMQ" width="40" height="40"/>
    </a> 
    <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> 
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/>
    </a> 
    <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer"> 
        <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="tailwind" width="40" height="40"/>
    </a> 
    <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"> 
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/>
    </a> 
</p>

**MongoDB:** armazenamento de informações sobre as tarefas

**NodeJS:** Backend
- Criação de tarefas POST /tasks
- Consulta de tarefas GET /tasks
- Exclusão de tarefas DELETE /tasks

**NextJS:** Frontend
- Visualização das tarefas com seu respectivo status
- Interromper execução de tarefa

**RabbitMQ:** Servindo como fila para as tarefas, uma forma alternativa ao banco de dados que com alto desempenho consegue armazenar e manter as tarefas a serem consumidas.

**Python**: Desenvolvimento do "**Agent**"
- Buscar a tarefa para executar, sempre que existirem
- Realizar o download do script python diretamente do GIT
- Montar o ambiente para a execução, de acordo com os requirements
- Executar o scipt
- Atualizar as informações do DB

**WebSocket**: uma forma de manter o sicronizmo entre o frontend e nosso "Agent"

## Autores
- [@henriqueweiss](https://www.github.com/henriqueweiss)
- [@matheusbarquette](https://www.github.com/matheusbarquette)
