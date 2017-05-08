<template>
    <div id="app">
        <navbar></navbar>
        
        <web-header></web-header>
        
        <about></about>
        
        <services></services>
        
        <most-popular></most-popular>
                
        <partners></partners>
        
        <contact></contact>
        
        <web-footer></web-footer>
    </div>
</template>

<script>
import Navbar from './components/Navbar'
import WebHeader from './components/Header'
import About from './components/About'
import Services from './components/Services'
import MostPopular from './components/MostPopular'
import Partners from './components/Partners'
import Contact from './components/Contact'
import WebFooter from './components/Footer'

export default {
    name: 'app',
    
    components: {
        Navbar,
        WebHeader,
        About,
        Services,
        MostPopular,
        Partners,
        Contact,
        WebFooter,
    },
}
</script>

<style>
    @import url('https://fonts.googleapis.com/css?family=Open+Sans');

    #app {
      font-family: 'Open Sans', sans-serif;
      -webkit-font-smoothing: antialiased;
      -moz-osx-font-smoothing: grayscale;
      color: #2c3e50;
    }

    .header-bg {
      background: url('./assets/header-bg.jpg');
      background-size: cover;
      width: 100%;
      background-repeat: no-repeat;
      padding: 70px;
      color: #fff;
      text-align: center;
    }

    .header-bg > h1 {
      font-weight: 700;
      line-height: 30px;
      letter-spacing: 1.5px;
      margin: 0 0 20px;
    }

    .header-bg > p {
      font-size: 16px;
      margin: 0 0 70px;
    }

    .header-bg > .search-box {
        display: block;
        padding: 15px 15px 0;
        margin-top: 0;
    }

    .btn-search {
      margin-bottom: 20px;
    }

    .section {
      padding: 2.3em 0 3em;
      border-bottom: 1px solid rgba(0,0,0,.05);
    }

    .section-bg-gray {
      background-color: #eaf1f1;
    }

    .title {
        color: #3c3c3c;
        text-align: center;
        text-transform: uppercase;
        padding-bottom: 1em;
        font-size: 2em;
        font-weight: 800;
        letter-spacing: 1px;
    }

    .title:after {
        display: inline-block;
        margin: 0 0 8px 20px;
        height: 3px;
        content: " ";
        text-shadow: none;
        background-color: #999;
        width: 140px;
    }
    .title:before {
        display: inline-block;
        margin: 0 20px 8px 0;
        height: 3px;
        content: " ";
        text-shadow: none;
        background-color: #999;
        width: 140px;
    }

    .section p {
      text-align: justify;
      margin-bottom: 1.5em;
    }

    .section .fa {
      margin-right: .2em;
    }
    
    .title-2 {
        color: #3c3c3c;
        text-align: center;
        text-transform: uppercase;
        font-size: 17px;
        letter-spacing: 2px;
        margin-bottom: 1.8em;
        line-height: 50px;
    }
</style>
