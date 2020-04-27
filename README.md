# AngularJson01_COD3R
Aplicação Angular com backend Json Server para CRUD de produtos

Inspirado na [playlist de aulas Angular](https://www.youtube.com/playlist?list=PLdPPE0hUkt0rPyAkdhHIIquKbwrGUkvw3) do canal de youtube [COD3RS Cursos](https://www.youtube.com/channel/UCcMcmtNSSQECjKsJA1XH5MQ).

> Neste curso gratuito iremos desenvolver uma APLICAÇÃO COMPLETA usando o Angular 9 e ao mesmo tempo entender os principais conceitos do framework!
> Falaremos sobre: Componentes, Diretivas, Services, Observables, RxJS, Pipes, Injeção de Dependência e muito mais.
>> COD3R Cursos

# Aulas youtube x aulas cod3r
- Algumas aulas são 100% teoria, então não teria código para atulaziar no github. Exemplo: Aula 01 - segunda parte do video [Angular 9 - Curso Grátis - Backend & Visão Geral do Angular [2020]](https://www.youtube.com/watch?v=NCrWXZtlc7Q&list=PLdPPE0hUkt0rPyAkdhHIIquKbwrGUkvw3&index=1)

- Alguns videos do Cod3r são agrupados no video do youtube, assim um video do youtube pode tar de dois a tres videos do cod3r:
  - Exemplo: Aula 06 do youtube equivale a aula 16 na contagem Geral e aula 12 no topico de Frontend;
  
- Estrutura videos Cod3r:
  - Introdução : 03 vídeos;
  - Backend : 01 vídeo;
  - FrontEnd: 39 vídeos;
  
- Aulas do youtube estão sendo publicadas aos poucos:
  - 22/004/2020 - Publicada Aula 05 youtube (Equivale à aula 10 de 39 do Frontend) :
    - [Angular 9 - Curso Grátis - Elementos do Angular #01 \[2020\]](https://www.youtube.com/watch?v=NgHu3ekeN_I&list=PLdPPE0hUkt0rPyAkdhHIIquKbwrGUkvw3&index=5)

  - 24/04/2020 - Publicada Aula 06 youtube (Equivale à aula 11 de 39 do Frontend) :
    - [Angular 9 - Curso Grátis - Elementos do Angular #02 \[2020\]](https://www.youtube.com/watch?v=LjNS1BgyEf4&list=PLdPPE0hUkt0rPyAkdhHIIquKbwrGUkvw3&index=6)
- [Commits](https://github.com/wfrsilva/AngularJson01_COD3R/commits/master): Em função de não ter aula no youtube, caso esteja a frente das publicações, usarei a contagem de videos do Frontend até o 39 (F-??/39):
  - Hoje, 24/04/2020, será [Aula F-12/39 :Elementos do Angular #03](https://www.cod3r.com.br/courses/take/angular-9-essencial/lessons/11778770-elementos-do-angular-03);



# Instalações primordiais
$ `npm i json-server`

$ `snap install postman`

$ `npm i -g @angular/cli`


# Instalações auxiliares

ngrok: para conseguir exibir seu localhost na web;
- $ `sudo snap install ngrok`

Grid Rule: Cria *grids* no navegador Chrome para facilitar medidas e alinhamentos;
- [Plugin Chrome Grid Rule](https://chrome.google.com/webstore/detail/grid-ruler/joadogiaiabhmggdifljlpkclnpfncmj?hl=pt-BR)  



# Comandos
$ `sudo apt install npm`
 
.../backend$ `npm init -y`

$ `npm start`

$ `ng new frontend --minimal`
> - Would you like to add Angular routing? (y/N) **Y**
> - **> CSS**
> - **CSS** | SCSS | Sass | Less | Stylus 

$ `cd frontend`
$ `ng serve`

http://localhost:4200/

$ `ng add @angular/material`
> - Choose a prebuilt theme name, or "custom" for a custom theme: (Use arrow keys)
> - **❯ Indigo/Pink        [ Preview: https://material.angular.io?theme=indigo-pink ]**
> -  Set up global Angular Material typography styles? (y/N) **Y**
> - Set up browser animations for Angular Material? (y/N) **Y**

frontend$ `ng generate component components/template/header`
> ou
> frontend$ `ng g c components/template/header`

frontend$ `ng g c components/template/footer`

frontend$ `ng g c components/template/nav`

frontend$ `ng g c views/home`

frontend$ `ng g d directives/red`

frontend$ `ng g d directives/for`

frontend$ `ng g c components/product/product-create`

frontend$ `ng g s components/product/product`

frontend$ `ng g c components/product/product-read`

frontend$ `ng g @angular/material:table components/product/product-readtable` video usou read2

frontend$ `ng g c components/product/product-update`





---

ngrok para visualizar projeto angular local (localhost) na web:

$ `ngrok http 4200 -host-header="localhost:4200"`

Tentando minimizar o uso de memoria do ng serve:

$ `node --max_old_space_size=2048 node_modules/@angular/cli/bin/ng serve --host 0.0.0.0`



# Referências Externas
- http://gitignore.io/api/angular
  - https://angular.io/guide/hierarchical-dependency-injection
  - https://material.angular.io/guide/schematics

- https://www.cod3r.com.br/courses/angular-9-essencial
- https://www.typescriptlang.org/
- https://material.io/resources/icons/?style=baseline
- https://chrome.google.com/webstore/detail/grid-ruler/joadogiaiabhmggdifljlpkclnpfncmj?hl=pt-BR
- [COD3R - (...) Entenda Flexbox!](https://www.youtube.com/watch?v=s-CARPA01NU&feature=youtu.be)
- https://unix.stackexchange.com/questions/128953/how-to-display-top-results-sorted-by-memory-usage-in-real-time






