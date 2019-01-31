# TPAzure-TP01Engenharia-Azure
Projeto Inicial de Azure TP01 - Asp Net - Exercicio 01 InfNet Engenharia da Computação


# Projeto de Exercicio para Desenvolvimento ASP .NET
Exercicio de Fixação


# Codificação HTML Index
--------------------------------------------------------------------------------------------------------
<!DOCTYPE html>
<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ExercicioTP01 - Azure e Asp.Net - Max Torres - Meu Aplicativo ASP.NET</title>
    <link href="/Content/css?v=XrM_i-qL7ntkoyZchCNCLeeyZEN21k6m7X1mfUibzPs1" rel="stylesheet"/>

    <script src="/bundles/modernizr?v=inCVuEFe6J4Q07A0AcRsbJic_UE5MwpRMNGcOtk94TE1"></script>

</head>
<body>
    <div class="navbar navbar-inverse navbar-fixed-top">
        <div class="container">
            <div class="navbar-header">
                <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
                
            </div>
            <div class="navbar-collapse collapse">
                <ul class="nav navbar-nav">
                    
                </ul>
            </div>
        </div>
    </div>
    <div class="container body-content">
        


<div class="jumbotron">
    <h1>Max Torres</h1>
    <p class="lead">engdevel2018@hotmail.com</p>
    <p><a href="https://asp.net" class="btn btn-primary btn-lg">Learn more &raquo;</a></p>
</div>

<div class="row">
    <div class="col-md-4">
        <h2>Software como Serviços (SaaS)</h2>
        <p>
            por vezes referido como “software sob demanda”, é um modelo de entrega
            de software no qual o software e seus dados associados são hospedados na
            internet (nuvem) e normalmente são acessados pelos usuários através de um
            thin client, normalmente usando um navegador web através da internet.
        </p>
        <h4>Exemplo:</h4>
        <p><b>Serviços de Aplicações:</b>Alguns exemplos são os serviço de email baseado na Web, como Outlook, Hotmail, são serviços SaaS.</p>
    </div>
    <div class="col-md-4">
        <h2>Plataforma como Serviço (PaaS)</h2>
        <p>
            Plataforma como serviço (PaaS) é a entrega de um ambiente de computação
            em camadas de soluções como serviço. Ofertas PaaS facilitam a implantação de
            aplicações de menor custo e complexidade na compra e gestão do hardware,
            software e recursos de provisionamento de infraestrutura, que fornece todas
            as facilidades necessárias para suportar o ciclo de vida completo de construção e
            entrega de aplicações web e serviços totalmente disponíveis a partir da Internet
        </p>
        <h4>Exemplo:</h4>
        <p><b>Serviços de Plataforma :</b> É possivel colocar um serviço Web com Aplicativos Web baseados em PHP, HTML, Node JS e até mesmo a suite LAMP.</p>
        
    </div>
    <div class="col-md-4">
        <h2>Infraestrutura como Serviço (IaaS)</h2>
        <p>
            Infraestrutura como serviço (IaaS) é uma maneira de entregar computação em
            nuvem, onde a infraestrutura de servidores, sistemas de rede, armazenamento, e
            todo o ambiente necessário para o funcionamento são contratados como serviços.
            Ao invés de comprar servidores, software, espaço em data center, os clientes
            usam estes recursos como um serviço totalmente terceirizado sob demanda.
        </p>
        <h4>Exemplo:</h4>
        <p><b>Seviços de Infraestrutura </b> É possivel ter toda a robustez de uma estrutura segura e com redundância. Possibilidade de Drives com Contas de Armazenamento publicas. </p>
    </div>
</div>
        <hr />
        <footer>
            <p>&copy; 2019 - Meu Aplicativo ASP.NET</p>
        </footer>
    </div>

    <script src="/bundles/jquery?v=2u0aRenDpYxArEyILB59ETSCA2cfQkSMlxb6jbMBqf81"></script>

    <script src="/bundles/bootstrap?v=lescQEuG5u4jd-GcVDBcbpUOSyTDIg0Kk9zHDX55GCw1"></script>

    
</body>
</html>

# Estrutura de Layout do Exercicio
-------------------------------------------------------------------------------------------------------------
<!DOCTYPE html>
<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>@ViewBag.Title - Meu Aplicativo ASP.NET</title>
    @Styles.Render("~/Content/css")
    @Scripts.Render("~/bundles/modernizr")
</head>
<body>
    <div class="navbar navbar-inverse navbar-fixed-top">
        <div class="container">
            <div class="navbar-header">
                <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
                
            </div>
            <div class="navbar-collapse collapse">
                <ul class="nav navbar-nav">
                    
                </ul>
            </div>
        </div>
    </div>
    <div class="container body-content">
        @RenderBody()
        <hr />
        <footer>
            <p>&copy; @DateTime.Now.Year - Meu Aplicativo ASP.NET</p>
        </footer>
    </div>

    @Scripts.Render("~/bundles/jquery")
    @Scripts.Render("~/bundles/bootstrap")
    @RenderSection("scripts", required: false)
</body>
</html>


