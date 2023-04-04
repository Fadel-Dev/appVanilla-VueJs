<script>
export default{}
</script>

<template>
       <section id="service" class="mx-5 text-gray-600">
            <h2 class="text-center py-16 text-4xl text-violet-700 ">NOS SERVICES</h2>
            <div class="containerService lg:grid grid-cols-3 gap-3 ">
                <div class="card ">
                    <div class="front">
                        <h2 class="text-violet-700">APPLIATION WEB/MOBILE</h2>
                        <img src="../assets/development.svg" alt="">

                    </div>
                    <div class="back">
                        <h2 class="text-violet-600">APPLIATION WEB/MOBILE</h2>

                        <p class="text-gray-400 text-left">
                            Si vous chercher un partenaire fiable pour la création
                            de vos applications web responsive <strong> (site e-commerce, site
                                vitrine, plateformes portfolio …)</strong> et <strong>mobile</strong>
                            multi-plateforme (Android,
                            iOS) <br> Vanilla js
                            /221 est l’endroit qu’il vous faut Nous sommes
                            engagés à fournir des solutions sur mesure qui
                            répondent à vos besoins spécifiques quelque soit votre secteur d’activité . </p>
                    </div>
                </div>
                <div class="card my-3 sm:my-1">
                    <div class="front">
                        <h2 class="text-violet-700">DESIGN GRAPHIC</h2>
                        <img class="w-3/4" src="../assets/design1.png" alt="">

                    </div>
                    <div class="back">
                        <h2 class="text-violet-700"> DESIGN GRAPHIC </h2>

                        <p class="text-gray-600 text-left">

                            Pour la création visuelle, Notre équipe créative peut travailler avec vous
                            pour des designs innovants,reflètant la personnalité et la marque de votre entreprise.
                            Nous avons des experts pour la création de vos <strong> logo, affiche,
                                flyers,charte Graphique, carte de visite, carte de mariage,tasses,Tee-shirt</strong>
                        </p>
                    </div>
                </div>

                <div class="card">
                    <div class="front" id="design">
                        <h2 class="text-violet-700">RESEAU TELECOM</h2>
                        <img src="../assets/network.svg" alt="">

                    </div>
                    <div class="back">
                        <h2 class="text-violet-700">RESEAU TELECOM</h2>

                        <p class="text-gray-600 text-left">

                            Pour vos installations etconfiguration des réseaux filaire ou sans fil ,Notre equipe vous
                            offres
                            des solutions de haute qualité pour assurer une connectivité rapide et fiable.
                            Nous fabriquons aussi des cables <strong>Rj11 ,Rj12 ,Rj45</strong>

                        </p>
                    </div>
                </div>
            </div>
        </section>
</template>

<style>
 * SERVICES */ #service h1 {
            text-align: center;
        }

        #service p {
            color: black;
            padding-top: 12px;
            padding-bottom: 29px;
        }

        #service h1+p {
            font-size: 19px;
        }

        #service {
            text-align: center;
            font-size: x-large;
        }

        #design {
            background-color: #fff;
            /* background: url('assets/images/development.svg');
    background-repeat: repeat; */
            background-size: contain;
        }

        #service img {
            width: 70%;
            height: auto;
        }



        .slideshow-container {
            max-width: 700px;
            position: relative;
            margin: auto;
        }

        .card {
            position: relative;
            width: 100%;
            height: 55vh;
            perspective: 19990px;



        }

        /* gallery */
        .grid .photo {
            display: grid;
            grid-template-columns: 32% 32% 32%;
            grid-gap: 2%;
        }

        .front,
        .back {
            position: absolute;
            width: 100%;
            height: 100%;
            backface-visibility: hidden;
            transition: transform 0.9s ease;
            padding: 2%;
            border-radius: 5%;
            border: 1px solid rgb(201, 196, 196);
        }

        .front {
            background-color: white;
            color: var(--primary-color);
        }

        .front img {
            width: 100%;
            margin: auto;
        }

        .back {
            color: var(--primary-color);
            background-color: #ffffff;
            transform: rotateY(180deg);
        }

        .back p {
            font-size: 19px;
            padding: 3%;
        }

        .card:hover .front {
            transform: rotateY(180deg);
        }

        .card:hover .back {
            transform: rotateY(0deg);
        }

        #contact {
            background-color: rgba(46, 2, 73, 1);
        }

      
        #contact .aa {
            background-color: rgba(208, 195, 220, 0.022);
        }
</style>