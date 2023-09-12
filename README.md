# Barbearia Alura 💇

Esse foi um projeto desenvolvido durante a primeira parte da Formação Front-end da Alura!
O site contém as páginas de: <strong>home</strong>, <strong>produtos</strong> e <strong>contato</strong>.

A página <strong>home</strong> possui:
<ul>
  <li>Informações sobre a barbearia Alura;</li>
  <li>Sobre o estabelecimento;</li>
  <li>Benefícios.</li>
</ul>
A página de <strong>produtos</strong> possui:
<ul>
  <li>Informações sobre os produtos;</li>
  <li>Preço sobre os produtos.</li>
</ul>
Já a última página de <strong>Contatos</strong> possui:
<ul>
  <li>Formulário de contato;</li>
  <li>Tabela de horários de funcionamento.</li>
</ul>
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width">
        <title>Contato | Barbearia Alura</title>
        <link rel="stylesheet" href="assets/css/reset.css">
        <link rel="stylesheet" href="assets/css/header.css">
        <link rel="stylesheet" href="assets/css/footer.css">
        <link rel="stylesheet" href="assets/css/contato.css">
        <link rel="stylesheet" href="assets/css/medias.css">
        <link rel="stylesheet" href="assets/css/body.css">
        <link href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap" rel="stylesheet">
    </head>
    <body>
        <header>
            <a href="#conteudoPrincipal">Pular para o conteúdo principal</a>
            <div class="caixa">
                <h1><img src="assets/img/logo.png" alt="Logo da barbearia Alura"></h1>
                <nav>
                    <ul>
                        <li><a href="index.html">Home</a></li>
                        <li><a href="produtos.html">Produtos</a></li>
                        <li><a href="contato.html">Contato</a></li>
                    </ul>
                </nav>
            </div>
        </header>

        <main>
            <form>
                <fieldset>
                    <label for="nome-sobrenome">Nome e Sobrenome</label>
                    <input type="text" id="nome-sobrenome" class="input-padrao" required>

                    <label for="telefone">Telefone</label>
                    <input type="tel" id="telefone" class="input-padrao" placeholder="(XX) XXXXX-XXXX"required>

                    <label for="email">E-mail</label>
                    <input type="email" id="email" class="input-padrao" placeholder="seuemail@seudomínio.com" required>

                    <label for="mensagem">Mensagem</label>
                    <textarea cols="75" rows="10" id="mensagem" class="input-padrao" required></textarea>
                </fieldset>

                <fieldset>    
                    <legend>Como prefere nosso contato?</legend>
                    <label for="radio-email"><input type="radio" name="contato" value="email" id="radio-email">E-mail</label>


                    <label for="radio-telefone"> <input type="radio" name="contato" value="telefone" id="radio-telefone">Telefone</label>


                    <label for="radio-whatsapp"><input type="radio" name="contato" value="whatsapp" id="radio-whatsapp" checked>WhatsApp</label>
                </fieldset>

                <fieldset>
                    <legend>Qual horário prefere ser atendido?</legend>
                    <select>
                        <option>Manhã</option>
                        <option>Tarde</option>
                        <option>Noite</option>
                    </select>
                </fieldset>

                <label for="checkbox"><input type="checkbox" class="checkbox" checked id="checkbox"> Gostaria de receber nossas novidades por e-mail?</label>

                <input type="submit" value="Enviar formulário" class="enviar">
            </form>

            <table>
                <thead>
                    <tr>
                        <th>Dia</th>
                        <th>Horário</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Segunda-feira</td>
                        <td>08h às 20h</td>
                    </tr>
                    <tr>
                        <td>Quarta-feira</td>
                        <td>08h às 20h</td>
                    </tr>
                    <tr>
                        <td>Sexta-feira</td>
                        <td>08h às 20h</td>
                    </tr>
                </tbody>
            </table>
        </main>
        <footer>
            <img src="assets/img/logo-branco.png" alt="Logo da barbearia Alura">
            <p class="Copyright">&copy;Copyright Barbearia Alura - 2021</p>
        </footer>
    </body>
</html>
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width">
        <title>Barbearia Alura</title>
        <link rel="stylesheet" href="assets/css/reset.css">
        <link rel="stylesheet" href="assets/css/home.css">
        <link rel="stylesheet" href="assets/css/header.css">
        <link rel="stylesheet" href="assets/css/footer.css">
        <link rel="stylesheet" href="assets/css/medias.css">
        <link rel="stylesheet" href="assets/css/body.css">
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap" rel="stylesheet">
    </head>
    <body>
        <header>
            <a href="#conteudoPrincipal">Pular para o conteúdo principal</a>
            <div class="caixa">
                <img src="assets/img/logo.png" alt="Logo barbearia Alura">
                <nav>
                    <ul>
                        <li>
                            <a href="index.html">Home</a>
                        </li>
                        <li>
                            <a href="produtos.html">Produtos</a>
                        </li>
                        <li>
                            <a href="contato.html">Contato</a>
                        </li>
                    </ul>
                </nav>
            </div>
        </header>
        <img class="banner"src="assets/img/banner.jpg" alt>
        <main>
            <section class="principal">
                <h1 class="titulo-principal" id="conteudoPrincipal">Sobre a Barbearia Alura</h1>
                <img class="utensilios" src="assets/img/utensilios.jpg" alt="Utensilios de um barbeiro">
                <h2> Localizada no coração da cidade a <strong>Barbearia Alura</strong> traz para o mercado o que há de melhor para o seu cabelo e barba. Fundada em 2019, a Barbearia Alura já é destaque na cidade e conquista novos clientes a cada dia.</h2>

                <h2 id="missao"><em>Nossa missão é: <strong>"Proporcionar auto-estima e qualidade de vida aos clientes".</strong></em></h2>

                <h2>Oferecemos profissionais experientes e antenados às mudanças no mundo da moda. O atendimento possui padrão de excelência e agilidade, garantindo qualidade e satisfação dos nossos clientes.</h2>
            </section>

            <section class="mapa">
                <h2 class="titulo-principal">Nosso estabelecimento</h2>
                <h3>Nosso estabelecimento está localizado no coração da cidade.</h3>
                <div class="mapa-conteudo">
                    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3656.448598130907!2d-46.634653385542435!3d-23.588239368469353!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x94ce5a2b2ed7f3a1%3A0xab35da2f5ca62674!2sCaelum%20-%20Escola%20de%20Tecnologia!5e0!3m2!1spt-BR!2sbr!4v1629377864050!5m2!1spt-BR!2sbr" width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
                </div>
            </section>
            <section class="beneficios">
                <h2 class="titulo-principal">Benefícios</h2>
                <div class="conteudo-beneficios">
                    <ul class="lista-beneficios">
                        <li class="itens">Atendimento aos clientes</li>
                        <li class="itens">Espaço diferenciado</li>
                        <li class="itens">Localização</li>
                        <li class="itens">Profissionais Qualificados</li>
                        <li class="itens">Pontualidade</li>
                        <li class="itens">Limpeza</li>
                    </ul><img class="imagem-beneficios" src="assets/img/beneficios.jpg" alt="Benefícios da Barbearia Alura">
                </div>
                <div class="video">
                    <iframe width="100%" height="315" src="https://www.youtube.com/embed/wcVVXUV0YUY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                </div>
            </section>

        </main>
        <footer>
            <img src="assets/img/logo-branco.png" alt="Logo da Barbearia Alura">
            <p class="Copyright">&copy;Copyright Barbearia Alura -2021</p>
        </footer>
    </body>
</html>
<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width">
        <title>Produtos | Barbearia Alura</title>
        <link rel="stylesheet" href="assets/css/reset.css">
        <link rel="stylesheet" href="assets/css/header.css">
        <link rel="stylesheet" href="assets/css/footer.css">
        <link rel="stylesheet" href="assets/css/produtos.css">
        <link rel="stylesheet" href="assets/css/medias.css">
        <link rel="stylesheet" href="assets/css/body.css">
        <link href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap" rel="stylesheet">
    </head>
    <body>
        <header>
            <a href="#conteudoPrincipal">Pular para o conteúdo principal</a>
            <div class="caixa">
                <img src="assets/img/logo.png" alt="Logo da barbearia Alura">
                <nav>
                    <ul>
                        <li><a href="index.html">Home</a></li>
                        <li><a href="produtos.html">Produtos</a></li>
                        <li><a href="contato.html">Contato</a></li>
                    </ul>
                </nav>
            </div>
        </header>
        <main>
            <ul class="produtos">
                <li>
                    <h1>Cabelo</h1>
                    <img src="assets/img/cabelo.jpg" alt>
                    <h2 class="produto-descricao">Na tesoura ou na máquina, como o cliente preferir</h2>
                    <h3 class="produtos-preco">R$ 25,00</h3>
                </li><!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width">
        <title>Produtos | Barbearia Alura</title>
        <link rel="stylesheet" href="assets/css/reset.css">
        <link rel="stylesheet" href="assets/css/header.css">
        <link rel="stylesheet" href="assets/css/footer.css">
        <link rel="stylesheet" href="assets/css/produtos.css">
        <link rel="stylesheet" href="assets/css/medias.css">
        <link rel="stylesheet" href="assets/css/body.css">
        <link href="https://fonts.googleapis.com/css2?family=Montserrat&display=swap" rel="stylesheet">
    </head>
    <body>
        <header>
            <a href="#conteudoPrincipal">Pular para o conteúdo principal</a>
            <div class="caixa">
                <img src="assets/img/logo.png" alt="Logo da barbearia Alura">
                <nav>
                    <ul>
                        <li><a href="index.html">Home</a></li>
                        <li><a href="produtos.html">Produtos</a></li>
                        <li><a href="contato.html">Contato</a></li>
                    </ul>
                </nav>
            </div>
        </header>
        <main>
            <ul class="produtos">
                <li>
                    <h1>Cabelo</h1>
                    <img src="assets/img/cabelo.jpg" alt>
                    <h2 class="produto-descricao">Na tesoura ou na máquina, como o cliente preferir</h2>
                    <h3 class="produtos-preco">R$ 25,00</h3>
                </li>
                <li>
                    <h1>Barba</h1>
                    <img src="assets/img/barba.jpg">
                    <h2   class="produto-descricao">Corte e desenho profissional de barba</h2>
                    <h3 class="produtos-preco">R$ 18,00</h3>
                </li>
                <li>
                    <h1>Cabelo + Barba</h1>
                    <img src="assets/img/cabelo+barba.jpg">
                    <h2 class="produto-descricao">Pacote completo de cabelo e barba</h2>
                    <h3 class="produtos-preco">R$ 35,00</h3>
                </li>
            </ul>
        </main>

        <footer>
            <img src="assets/img/logo-branco.png" alt="Logo barbearia Alura">
            <p class="Copyright">&copy;Copyright Barbearia Alura - 2021</p>
        </footer>
    </body>
</html>
                <li>
                    <h1>Barba</h1>
                    <img src="assets/img/barba.jpg">
                    <h2   class="produto-descricao">Corte e desenho profissional de barba</h2>
                    <h3 class="produtos-preco">R$ 18,00</h3>
                </li>
                <li>
                    <h1>Cabelo + Barba</h1>
                    <img src="assets/img/cabelo+barba.jpg">
                    <h2 class="produto-descricao">Pacote completo de cabelo e barba</h2>
                    <h3 class="produtos-preco">R$ 35,00</h3>
                </li>
            </ul>
        </main>

        <footer>
            <img src="assets/img/logo-branco.png" alt="Logo barbearia Alura">
            <p class="Copyright">&copy;Copyright Barbearia Alura - 2021</p>
        </footer>
    </body>
</html>
