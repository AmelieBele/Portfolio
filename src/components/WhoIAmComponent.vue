<template>    
    <div class="container">
        <h1><span>const </span>Qui suis-je ?<span>=</span></h1>
        <p>
            Je suis Amélie, développeur web junior. J'ai, juste après mon bac, décider d'arrêter mes études et me suis dirigé vers le commerce 
            puis-qu'une occasion s'est présentée à moi. Dans le prêt-à-porter puis dans l'alimentaire, j'ai fini par en avoir assez vu et 
            j'ai donc décidé de reprendre mes études. J'ai appris le métier via une formation condensée, comme on en entend beaucoup parler, 
            mais malgré mon manque d’expérience professionnelle, cela n’entame en rien ma motivation, au contraire, cela me pousse encore 
            plus à faire mes preuves. Il est temps pour moi d'entrer dans le monde du travail avec ce 
            nouveau diplôme en poche et de trouver l'employeur qui me laissera ma chance. Je suis hyper impatiente à l'idée d'enfin entrer
            dans ce nouveau milieu et surtout, j'ai envie d'apprendre encore plus !<span>;</span>
        </p>
    </div>
</template>

<script>

export default {
  name: 'WhoIAmComponent',

}

</script>

<style lang="scss" scoped>
    .container{

        margin: 70px;

        span{
            color: #700817;
            font-family: 'La belle Aurore', sans-serif;
            font-size:1rem;
        }
        p{
            margin-top:30px;

        }

    }
</style>
