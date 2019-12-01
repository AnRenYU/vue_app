<template>
  <div>

       <header class="">
             <div class="navbar navbar-default visible-xs">
               <button type="button" class="navbar-toggle collapsed">
                 <span class="sr-only">Toggle navigation</span>
                 <span class="icon-bar"></span>
                 <span class="icon-bar"></span>
                 <span class="icon-bar"></span>
               </button>
               <a href="/" class="navbar-brand">极速视频网络平台</a>
             </div>
           
             <nav class="sidebar">
               <div class="navbar-collapse" id="navbar-collapse">
                 <div class="site-header hidden-xs">
                     <a class="site-brand" href="./index.html" title="">
                       <img class="img-responsive site-logo" alt="" src="../assets/assets_2/images/mashup-logo.svg">
                       极速视频网络平台
                     </a>
                   <p>
                     视频分类
           
                   </p>
                 </div>
                 <ul class="nav">
                   <li><a href="./index.html" title="">首页</a></li>
                   <li><a href="./about.html" title="">视频详情页</a></li>
                   <li><a href="./services.html" title="">Services</a></li>
                   <li><a href="./contact.html" title="">Contact</a></li>
                   <li><a href="./components.html" title="">Components</a></li>
           
                 </ul>
           
                 <nav class="nav-footer">
                   <p class="nav-footer-social-buttons">
                     <a class="fa-icon" href="https://www.instagram.com/" title="">
                       <i class="fa fa-instagram"></i>
                     </a>
                     <a class="fa-icon" href="#" title="">
                       <i class="fa fa-dribbble"></i>
                     </a>
                     <a class="fa-icon" href="#" title="">
                       <i class="fa fa-twitter"></i>
                     </a>
                   </p>
                 </nav>  
               </div> 
             </nav>
             </nav>
           </header>

    <main class="" id="main-collapse">

    <div class="hero-full-wrapper">
       <div v-masonry transition-duration="0.3s" item-selector=".grid-item" class="grid">
       <div class="gutter-sizer"></div>
         <div class="grid-sizer"></div>
         
         <div v-masonry-tile class="grid-item">
           <img class="img-responsive" alt="" src="../assets/assets_2/images/img-12.jpg">
           <a href="./project.html" class="project-description">
             <div class="project-text-holder">
               <div class="project-text-inner">
                 <h3>视频标题</h3>
                 <p>视频简介</p>
               </div>
             </div>
           </a>
         </div>
     
         
         <div class="grid-item">
           <img class="img-responsive" alt="" src="../assets/assets_2/images/img-05.jpg">
           <a href="./project.html" class="project-description">
             <div class="project-text-holder">
               <div class="project-text-inner">
                 <h3>Vivamus vestibulum</h3>
                 <p>Discover more</p>
               </div>
             </div>
           </a>
         </div>
        
         <div class="grid-item">
           <img class="img-responsive" alt="" src="../assets/assets_2/images/img-13.jpg">
           <a href="./project.html" class="project-description">
             <div class="project-text-holder">
               <div class="project-text-inner">
                 <h3>Vivamus vestibulum</h3>
                 <p>Discover more</p>
               </div>
             </div>
           </a>
         </div>
         <div class="grid-item">
           <img class="img-responsive" alt="" src="../assets/assets_2/images/img-04.jpg">
           <a href="./project.html" class="project-description">
             <div class="project-text-holder">
               <div class="project-text-inner">
                 <h3>Vivamus vestibulum</h3>
                 <p>Discover more</p>
               </div>
             </div>
           </a>
         </div>
         
         <div class="grid-item">
           <img class="img-responsive" alt="" src="../assets/assets_2/images/img-07.jpg">
           <a href="./project.html" class="project-description">
             <div class="project-text-holder">
               <div class="project-text-inner">
                 <h3>Vivamus vestibulum</h3>
                 <p>Discover more</p>
               </div>
             </div>
           </a>
         </div>
     
         <div class="grid-item">
           <img class="img-responsive" alt="" src="../assets/assets_2/images/img-11.jpg">
           <a href="./project.html" class="project-description">
             <div class="project-text-holder">
               <div class="project-text-inner">
                 <h3>Vivamus vestibulum</h3>
                 <p>Discover more</p>
               </div>
             </div>
           </a>
         </div>
     
         <div class="grid-item">
           <img class="img-responsive" alt="" src="../assets/assets_2/images/img-10.jpg">
           <a href="./project.html" class="project-description">
             <div class="project-text-holder">
               <div class="project-text-inner">
                 <h3>Vivamus vestibulum</h3>
                 <p>Discover more</p>
               </div>
             </div>
           </a>
         </div>
         <div class="grid-item">
           <img class="img-responsive" alt="" src="../assets/assets_2/images/img-03.jpg">
           <a href="./project.html" class="project-description">
             <div class="project-text-holder">
               <div class="project-text-inner">
                 <h3>Vivamus vestibulum</h3>
                 <p>Discover more</p>
               </div>
             </div>
           </a>
         </div>
     
     
         
       </div>
     </div>
    </main>

    

  

  </div>
</template>


 
<script>

export default {
  data () {
    return {
      msg: "这是一个变量",
      dataList:[],
      clicked:0,
      upath: '',
    result: '',
    uping:0
    }
  },
  mounted:function(){
  

},
  methods:{
      changetest(index){
          this.clicked = index;
      }
  }
}


</script>
 
<style>



</style>