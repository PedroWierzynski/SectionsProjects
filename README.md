# SectionsProjects
Sections -> HTML, CSS and JS


<!-- SECTION CARD -->
<!-- Html -->

<div class="container">
    <section id="topics" class="padding-section">
        <div class="row">
            <div class="col-md-4 col-sm-12">
                <div class="card">
                    <img class="center-img" width="80px" height="80px" src="">
                    <div class="card-body">
                        <h5>Segurança</h5>
                        <p>Temos os melhores desenvolvedores de softwares para garantir a total segurança do seu        investimento</p>
                       
                    </div>    
                </div>
            </div>
            <div class="col-md-4 col-sm-12">
                <div class="card">
                    <img class="center-img" width="80px" height="80px" src="/assets/images/icons/purse.svg">
                    <div class="card-body">
                        <h5>Depósitos</h5>
                        <p>Faça seu depósito pela internet, com total segurança e discrição</p>
                       
                    </div>    
                </div>
            </div>
            <div class="col-md-4 col-sm-12">
                <div class="card">
                    <img class="center-img" width="80px" height="80px" src="/assets/images/icons/customer-support.svg">
                    <div class="card-body">
                        <h5>Suporte</h5>
                        <p>A melhor equipe de suporte, para atendê-lo e suprir todas as suas duvidas</p>
                       
                    </div>    
                </div>
            </div>
        </div>
    </section>
</div>

<!-- CSS -->
body{
background-color: white;
font-family: 'Roboto Condensed', sans-serif;

}
.container{
	margin-left: auto;
	margin-right: auto;
}
h5{
	font-size: 20px;
	color: black;
	padding: 10px 0px;
	font-weight: bolder;
}
p{
	font-size: 15px;
	color: #fff;
}
.card {
    position: relative;
    display: -ms-flexbox;
    display: flex;
    -ms-flex-direction: column;
    flex-direction: column;
    min-width: 0;
    word-wrap: break-word;
    background-color: #fff;
    background-clip: border-box;
    border: 2px solid #debf27!important;
    border-radius: 5px!important;
    height: 300px;
    text-align: center;

}
.card p{
color: black;
font-size: 15px;
padding: 10px 0px 20px;
}
.center-img{
	margin: 20px auto;
}
.card:hover{
	background-color: #17a2b8;

}
.card:hover p{
	color: #fff;

}
.card:hover h3{
	color: #fff;

}


