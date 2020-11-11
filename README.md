# JAVATestesUnitarios
Exemplo de testes unitários em Java

 No Intellij criar projeto com Maven, na classe criada que quero testar:
#### Va na aba Navigate -> Test -> Create New Test

No pom.xml importar as dependencias:
```
  <dependencies>
        <dependency>
            <groupId>junit</groupId>
            <artifactId>junit</artifactId>
            <version>RELEASE</version>
            <scope>compile</scope>
        </dependency>

        <dependency>
            <groupId>org.mockito</groupId>
            <artifactId>mockito-core</artifactId>
            <version>3.3.3</version>
            <scope>test</scope>
        </dependency>

        <dependency>
            <groupId>org.easymock</groupId>
            <artifactId>easymock</artifactId>
            <version>4.2</version>
            <scope>test</scope>
        </dependency>

        <dependency>
            <groupId>org.hamcrest</groupId>
            <artifactId>hamcrest-all</artifactId>
            <version>1.3</version>
        </dependency>

        <dependency>
            <groupId>org.assertj</groupId>
            <artifactId>assertj-core</artifactId>
            <version>3.4.1</version>
            <scope>test</scope>
        </dependency>
    </dependencies>
    ```
