<div> 
<p><a href="https://github.com/JosiTubaroski/Controllers_Services/blob/main/README.md">Home</a></p>
</div> 

- Criar a Interface IAutorInface.cs

<img src="https://github.com/JosiTubaroski/Controllers_Services/blob/main/img/04_InterfaceAutor.png"/>

<img src="https://github.com/JosiTubaroski/Controllers_Services/blob/main/img/05_Menu_Interface.png"/>

# IAutorInterface.cs

Veja o código da AutorInterface.cs 👉 https://github.com/JosiTubaroski/Controllers_Services/blob/main/img/IAutorInterface.cs

### 🔹 O que esse código faz?

Ele define <b>uma interface chamada</b> IAutorInterface. Essa interface declara três métodos assíncronos relacionados a manipulação de <b>Autores.</b>

### 🔹 Explicação linha por linha

- 1️⃣ using WebAPI8_Video.Models;

Essa linha importa o namespace WebAPI8_Video.Models, que contém classes de modelos (provavelmente AutorModel e ResponseModel).

- 2️⃣ namespace WebAPI8_Video.Services.Autor

Define um <b>namespace</b> para organizar o código. Aqui, ele indica que esse código faz parte do módulo de <b>Serviços de Autor</b> dentro do projeto <b>WebAPI8_Video.</b>

- 3️⃣ public interface IAutorInterface

Declara uma <b>interface</b> chamada IAutorInterface.

- ✅ Interfaces definem contratos que as classes devem seguir.
- ✅ Essa interface será implementada por um Service que executará a lógica.

- 4️⃣ Métodos da Interface

  Agora, vamos ver os <b>métodos</b> que essa interface exige que uma classe implementadora defina.

   Task<ResponseModel<List<AutorModel>>> ListarAutores();

### 🔹 Conclusão

- ✅ Esse código define um contrato (IAutorInterface) que uma classe de serviço deve seguir para lidar com <b>Autores.</b>
- ✅ Ele organiza a API de forma <b>modular, reutilizável e testável.</b>
- ✅ Usa um <b>ResponseModel</b> para padronizar as respostas da API.

