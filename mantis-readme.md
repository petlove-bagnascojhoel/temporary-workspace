![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/ae16de35-bd5d-489f-b8ee-53fca0d1e989/9a8af36f-7f8f-4b77-8ad9-c7cbf819072a/Untitled.png)

# mantis

## Back-End do ERP Vetus

Vetus ERP é um ERP (Enterprise Resource Planning) para pet shops e clínicas veterinárias. Possui funcionalidades de:

- Gerenciamento de serviços (ex. tosa, banho, consulta clínica, cirurgia, …), desde agendamento ao pagamento.
- Realização de vendas, geração de notas fiscais.
- Manuseio, auditoria, validação, compras e transações de estoque.
- Gerenciamento de múltiplas lojas ou clínicas através de um único acesso.
- Ações de marketing personalizado através e mensagens de texto.

## Technologies

<p align="center">
<img src="https://raw.githubusercontent.com/petlove/vetus-assets/master/gif/dog-computer.gif"
align="center" alt="Code Review" width="600" >
</p>

<br>

At Vetus, we use the following stack:

- **Spring Boot**: An open source Java-based framework used to create a micro Service.
It is developed by Pivotal Team and is used to build stand-alone and production ready spring applications.
- **CodeFresh as CI**: DevOps automation platform brings CI/CD, Kubernetes, GitOps and more to help companies
confidently deploy software faster.
- **PostgreSQL Database**: Open source object-relational database system that uses and extends the SQL language combined with
many features that safely store and scale the most complicated data workloads.

### Running the Project as Spring Boot Project

To be able to run the project as a Spring Boot Project, have in mind that you should have Java and Gradle
installed on your computer. The installment instructions are available below. For now, instructions are available for
Linux environments (Ubuntu). Further instructions for other OS will be added.

1. Install the `sdk man` to simplify setup:
    
    ```
    <https://sdkman.io/install>
    
    ```
    
2. Install Java 11:
    
    ```
    <https://sdkman.io/usage>
    
    ```
    
3. Verify if the installation was successful:
    
    ```
    $ java -version
    
    ```
    
    ```
    openjdk version "11.0.12" 2021-07-20
    OpenJDK Runtime Environment 18.9 (build 11.0.12+7)
    OpenJDK 64-Bit Server VM 18.9 (build 11.0.12+7, mixed mode)
    
    ```
    
4. We use Google Cloud Artifact Registry to host our
5. to run the project, set the necessary environment variables (ask for Tech Lead):
    
    ```
       $ gradle clean compileJava
    
    ```
    

</details>

## Contributing

<p align="center">
<img src="https://raw.githubusercontent.com/petlove/vetus-assets/11404617102b0296516b72c9659ca35efd95876d/svg/undraw_good_doggy.svg"
alt="Good Doggy"
width="738">
</p>

- Fork this repo!
- Hack away!
- Create a new pull request using `https://github.com/petlove/vetus-erp/compare`
