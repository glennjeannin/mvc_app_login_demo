<template class =login-template>
    <div class="background">
        <div class="vue-template center-div center-div-vetical">
        <form>
            <h3>Connexion</h3>
            <div class="form-group">
                <label>Adresse mail</label>
                <input type="email" class="form-control form-control-lg" />
            </div>
            <div class="form-group">
                <label>Mot de passe</label>
                <input type="password" class="form-control form-control-lg" />
            </div>
            <button type="submit" class="btn btn-dark btn-lg btn-block">Sign In</button>
            <div class="icone-reseaux">
                <ul>
                    <li><a href="https://www.linkedin.com/in/glenn-jeannin-57691812a"><i class="fa fa-linkedin"></i></a></li>
                    <li><a href="https://www.facebook.com/glenn.jeannin"><i class="fa fa-facebook"></i></a></li>
                    <li><a href="https://universweb.re"><i class="fa fa-globe"></i></a></li>
                </ul>
            </div>
        </form>
    </div>
    </div>
    
</template>
<script>
    export default {
        data() {
            return {}
        }
    }
</script>