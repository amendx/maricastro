# maricastro

## Começando

Antes de tudo, suponho que já tenha familiaridade com o **git** e já tenha tudo preparado. 

Caso contrário:
1. [Crie uma conta](https://github.com/)
2. [Adicione o git em sua máquina (WINDOWS + VSCode)](https://www.geeksforgeeks.org/how-to-install-git-in-vs-code/)
> Verifique se foi adicionar com sucesso
  ```shell
    git config --list
  ```
  Deverá retornar suas informações, como por exemplo:
  ```shell
  user.name=Mari castro
  user.email=maricastro@email.com
  ```

3. **Clone** o projeto para sua máquina
```shell
git clone https://github.com/amendx/maricastro.git
```
  ![image](https://user-images.githubusercontent.com/30783877/209546249-aab9304a-3031-457a-877f-35d43bdf0aff.png)

4. Entre na pasta `maricastro`

```shell
cd maricastro
```
![image](https://user-images.githubusercontent.com/30783877/209546614-9e3c963d-931c-4771-bdb4-c4c1b4cb3ed0.png)

> Para se certificar que tudo deu certo:
```shell
git remote -v
```
![image](https://user-images.githubusercontent.com/30783877/209546729-83c88bdf-c499-4044-8132-f371a277cfad.png)

5. Adicione o seu código à pasta, em seguida:
```shell
git status
```
![image](https://user-images.githubusercontent.com/30783877/209546805-61b2fbae-3621-462c-b803-f67705924e3e.png)
> Ao adicionar a sua pasta/arquivos à nova pasta, algo do tipo deverá ser listado, seja um diretório ou uma lista de novos arquivos que voc

```shell
git add .
git status
```
![image](https://user-images.githubusercontent.com/30783877/209547058-fb94bee9-2966-4378-8786-5471502db131.png)
> Você deverá ver agora uma lista de arquivos/diretórios verde, sinalizando que os arquivos foram localizados e estão prontos para ir ao repo

Em seguida, adicione uma nova branch, por exemplo `mari-codigo`:
```shell
git checkout -b mari-codigo
```
![image](https://user-images.githubusercontent.com/30783877/209547162-842ea530-d75d-4e1c-83c9-faff5f80bac8.png)
> Você deverá ver que agora nossa referência saiu de `main` para `amanda-teste`

- Adicione o código remotamente ao repositório, onde o que vai dentro das aspas é um breve comentário desse "upload":
```shell
git commit -m "Teste de código"
```

![image](https://user-images.githubusercontent.com/30783877/209547253-05ef8b86-a0e0-460f-85e6-3b756b6d67c6.png)

6. Mande o código recém adicionado para o repositório na nuvem
```shell
git push origin mari-codigo
```
![image](https://user-images.githubusercontent.com/30783877/209547305-4342f81b-e7c6-4007-b14a-aa570f79f441.png)

7. Após o envio com sucesso, entre novamente no repositório com sua conta logada no GitHub e verifique se sua nova branch aparece com essa sugestão: 

![image](https://user-images.githubusercontent.com/30783877/209547359-d2122a3a-e76e-4e96-82ec-cee9d26b81ea.png)

8. Clique em **Compare & Pull request**
> Escreva uma breve descrição do seu código, o que gostaria que fosse validado/visto, pontos de atenção e ou configuração:

![ezgif com-gif-maker(2)](https://user-images.githubusercontent.com/30783877/209549419-9b1c2eb6-883f-498c-b5d3-5da17004dfdf.gif)

9. Descendo um pouco a página, você poderá ver todos os arquivos adicionados
![image](https://user-images.githubusercontent.com/30783877/209547565-10f8f03c-c1c6-46cb-8626-90924a0234b7.png)

10. Se tudo estiver de acordo, seu código está prontinho pra ser revisado :rocket: :sparkles:
![image](https://user-images.githubusercontent.com/30783877/209547619-89303006-f48e-4d60-8f75-1e547c725d8d.png)



