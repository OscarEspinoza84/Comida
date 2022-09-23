<template>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.0/css/all.min.css">
    <h1>Comida Rapida</h1>
    <hr> 

    


    <center>
    <card url="https://www.unileverfoodsolutions.com.mx/dam/global-ufs/mcos/NOLA/calcmenu/recipes/MX-recipes/In-Development/FULL-ALITAS.png " nombre="Alitas"  costo="$80"  descripcion="BBF , BBQ , LimonPP , Mango "  />

    <card url="https://www.saborusa.com/wp-content/uploads/2019/10/Animate-a-disfrutar-una-deliciosa-pizza-de-salchicha-Foto-destacada.png" nombre="Pizza" costo="$110" descripcion="Queso , Peperonie , Mexicana "/>

    <card url="https://mexico.didiglobal.com/wp-content/uploads/sites/5/2022/02/tacos-de-carnitas.jpg.jpg" nombre="Tacos " costo="$50"    descripcion=" Tacos de bistec / Torilla de arina y Maiz  "/>
     <br>
    <card url=" https://www.soriana.com/dw/image/v2/BGBD_PRD/on/demandware.static/-/Sites-soriana-grocery-master-catalog/default/dw4a12f983/images/product/0261610000006_A.jpg?sw=1000&sh=1000&sm=fit" nombre="Pastel"  costo="$40"    descripcion=" Pastel de 3 leches "/>

    <card url=" " nombre="Hamburgesa" costo="$90"  descripcion="BfF , BBQ , Especial , Mexicana"/>

    <card url=" " nombre="Ensalada"  costo="$60"   descripcion="Pollo , Atun , Quesos "/>
</center>

<br><br>
<footer class="bg-dark text-white pt-5 pb-4">
        <div class="container text-center text-md-left">
            <div class="row text-center text-md-left">
                <div class="col-md-3 col-lg-3 col-xl-3 mx-auto- mt-3">
                    <h5 class="text-uppercase mb-4 font-weight-bold text-warning"> Fast Food</h5>
                     <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Praesentium voluptatem necessitatibus qui, in voluptates placeat obcaecati ea tempore neque natus nobis iusto sequi pariatur nihil amet eos ut libero eligendi? </p>
                </div> 
                <div class="col-md-2 col-lg-2 col-xl-2 mx-auto mt-3">
                    <h5 class="text-uppercase mb-4 font-weight-bold text-warning">Productos</h5>
                    <p>
                        <a href="#" class="text-white" style="text-decoration : none;">The provident</a>
                    </p>
                    
                    <p>
                        <a href="#" class="text-white" style="text-decoration : none;">The provident</a>
                    </p>
                    
                    <p>
                        <a href="#" class="text-white" style="text-decoration : none;">The provident</a>
                    </p>
                    
                    <p>
                        <a href="#" class="text-white" style="text-decoration : none;">The provident</a>
                    </p>

                </div>

                <div class="col-md-3 col-lg-2 col-xl-2 mx-auto mt-3">
                    <h5 class="text-uppercase mb-4 font-weight-bold text-warning">Productos</h5>
                    <p>
                        <a href="#" class="text-white" style="text-decoration : none;">The provident</a>
                    </p>
                    
                    <p>
                        <a href="#" class="text-white" style="text-decoration : none;">The provident</a>
                    </p>
                    
                    <p>
                        <a href="#" class="text-white" style="text-decoration : none;">The provident</a>
                    </p>
                    
                    <p>
                        <a href="#" class="text-white" style="text-decoration : none;">The provident</a>
                    </p>

                </div>

                <div class="col-md-4 col-lg-2 col-xl-2 mx-auto mt-3">
                    <h5 class="text-uppercase mb-4 font-weight-bold text-warning">Productos</h5>
                    <p>
                        <i class="fas fa-home mr-3">  Puebla city , MX </i>
                    </p>
                    
                    <p>
                        <i class="fas fa-envelope mr-3" >  FasFood@gamil.com</i>
                    </p>
                    
                    <p>
                        <i class="fas fa-phone mr-3">  +52 238 155 0346</i>
                    </p>
                    
                    <p>
                        <i class="fas fa-print mr-3">  Av.Reforma N.303 Tehuacan,Pue</i>
                    </p>

                </div>
                <hr class="mb-4">

                <div class="row aling-items-center">
                    <div class="col-md-7 col-lg-8">
                        <p> Copyrith @2022  OSCAR URIEEL ESPINOZA PULIDO 4B:
                        <a href="#" style="text-decoration:none;"> 
                        <strong class="text-warning">THE FOOD MX </strong>
                        </a></p>
                    </div>

                    <div class="col-md-5 col-lg-4">
                        <div class="text-center text-md-right">
                            <ul class="list-unstyled list-inline">
                                <li class="list-inline-item">
                                    <a href="#" class="btn-floating btn-sm text-white " style="font-size:23px;"><i class="fab fa-facebook"> </i></a>
                                </li>
                                <li class="list-inline-item">
                                    <a href="#" class="btn-floating btn-sm text-white " style="font-size:23px;"><i class="fab fa-twitter"> </i></a>
                                </li>
                                <li class="list-inline-item">
                                    <a href="#" class="btn-floating btn-sm text-white " style="font-size:23px;"><i class="fab fa-instagram"> </i></a>
                                </li>
                                
                            </ul>
                            
                        </div>
                    </div>


                </div>
            </div>
        </div>
    </footer>




</template>


<script>
 import Card from "./components/Card.vue"
 export default {
    components: { 
        Card 
    },
 };
</script>