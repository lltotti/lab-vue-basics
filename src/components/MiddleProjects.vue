<template>
 <section class="hero">
        <section class="container">
            <section class="content">
                <div>
                    <h1 class="font-h1-60Bold"> Empower Your Business With Stunning Design!
                    </h1>
                </div>
                <div>
                    <p class="font-BodyIntoTxt20Reg" id="content_p1"> Circle is a digital design and development studio. We design and develop astonishing websites and mobile apps.
                    </p>
                </div>                
                <div class="hero-content-buttons-div">
                    <div class="btn-blue" id="btn-hero">
                        <a href="" class="font-hdlTxt17Med btn-link">Get in touch
                        </a>
                    </div>
                    <span></span>
                    <div id="content_p2">
                        <a href="" class="font-hdlTxt17Med">
                            See our work
                        </a>
                    </div>
                </div>
                
              
            </section>
            <section class="image">
                <img id="img-card-1" src="../assets/images-icons/hero-section/card-1.png">
                <img id="kkk" src="../assets/images-icons/hero-section/hero-image.png">
                <img id="img-card-2" src="../assets/images-icons/hero-section/card-2.png">
                             
            </section>
        </section>
 </section>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
/* @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100&display=swap'); */

@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;700&display=swap');

/*FONTS*/
.font-h1-60Bold{
    font-family: 'Roboto', sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 60px;
    line-height: 70px;
    color: #514D67;
    /*Atenção*/
    margin:0px; 
}
.font-h2-50Bold{
    font-family: 'Roboto', sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 50px;
    line-height: 59px;
    /* identical to box height */
    color: #514D67;
}

.font-H3-40bold{
    font-family: 'Roboto', sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 40px;
    line-height: 47px;
     /* Neutral/Dark */
    color: #292E47;
    margin: 0px;
}

.font-H4-24Bold{
    font-family: 'Roboto', sans-serif;
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 28px;
    color: #514D67;
}

.font-BodyIntoTxt24Mid{
    font-family: 'Roboto', sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 24px;
    line-height: 28px;
    /* Neutral/Dark */
    color: #292E47;
}

.font-BodyIntoTxt20Reg{
    /* Body/Regular */
    font-family: 'Roboto', sans-serif;
    font-style: normal;
    font-weight: normal;
    font-size: 20px;
    line-height: 150%;
    /* or 30px */
    /* Neutral/Medium */
    color: #6B708D;
}

.font-HdlTxt17Reg{
    font-family: 'Roboto', sans-serif;
    font-style: normal;
    font-weight: normal;
    font-size: 17px;
    line-height: 150%;
    /* identical to box height, or 26px */
    color: #514D67;
}
.font-hdlTxt17Med {
    /* Headline/Medium */
    font-family: 'Roboto', sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 17px;
    line-height: 130%;
    /* identical to box height, or 22px */
    /* Neutral/Medium */
    color: #6B708D;
}

.font-Cap1Txt15Reg{
    font-family: 'Roboto', sans-serif;
    font-style: normal;
    font-weight: normal;
    font-size: 15px;
    line-height: 18px;
    /* identical to box height */
    color: #514D67;
}

.font-Cap2Txt13Reg{
    font-family: 'Roboto', sans-serif;
    font-style: normal;
    font-weight: normal;
    font-size: 13px;
    line-height: 15px;
    color: #514D67;
}

body {
    background-color: #F2F4FC;
    margin:0px;
    padding:0px;
    
}
header{
    max-width: 100%;
    height: 122px;
    /* border: 5px solid fuchsia;   */
        
}
.mini-head{
    /* position: absolute; */
    max-width: 1100px;
    margin-left: auto;
    margin-right:auto;
    margin-top: 70px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    /* border: 1px solid saddlebrown;   */
}

header img{
    width: 60.53px;
    height: 18.46px;
}

nav{
display: flex;
flex-direction: row;
justify-content: space-between;
align-items: flex-end;
padding: 0px;
width: 295px;
height: 22px;
}

nav a{
    /* Font-Format */
    font-family: 'Roboto', sans-serif;
    color: #6B708D;
    text-decoration:none;
}
nav a:hover{
    color:#072AC8;
}

.btn-blue{
/* Auto layout */
display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
padding: 1px 1px;

/* position: absolute; */
width: 150px;
height: 52px;
/* left: 1120px;
top: 70px; */


/* Primary/Default */
background: #072AC8;
}

.btn-link {
    text-decoration: none;
    color: #FFFFFF;
    padding: 15px 20px;
}

.hero{
    /* position: absolute; */
    max-width: 100%;
    /* max-height: 650px; */
    /* left: calc(50% - 1440px/2); */
    margin-left:auto;
    margin-right:auto;
    margin-top: 98px;
    /* top: 226px; */
    /* border: 3px solid rgb(231, 35, 35);  */
}

.container{
    display: flex;
    flex-direction: row;
    justify-content: left;
       
    /* position: absolute; */
    max-width: 1100px;
    max-height: 650px;
    /* left: 170px; */
    /* top: 0px; */
    /* border: 5px solid orange;  */
    margin-left: auto;
    margin-right: auto;
}

.content{
    /* position: absolute; */
    display: flex; 
    flex-direction: column;
    /* max-width: 530px; */
    /* max-height: 422px; */
    /* left: 170px; */
    /* left:calc(calc(50% - 1440px/2)*170px); */
    /* top: 109px; */
     /* border: 2px solid blue;  */
     margin: 0px;
}

.image{
    display: flex;
    flex-direction: row;
    justify-content: space-between;    
  /* justify-items: space-between; */
    /* position: relative;     */
    /* Image */
  /* position: absolute; */
  /* width: 570px; */
  /* max-width: 570px; */
  /* max-height: 650px; */
  /* left: 700px; */
  /* left:530px; */
  /* top: 0px; */
   /* border: 5px solid green;  */
   /* background-image: url("images-icons/hero-section/hero-image.png");  */
  
  /* background-color: green; */
  /* background-size: cover;   */
  /* position: 0 0; */
  /* background-repeat: no-repeat;  */
  /* transform: matrix(-1, -0.02, -0.02, 1, 0, 0); */
}

.hero-content-buttons-div{
    display: flex;
    flex-direction: row;
    /* border: 3px solid gray; */
    /* margin:0px; */
    /* align-items: center; */
}
#img-card-1{
    position: absolute;
    max-width: 190px;
    height: 216px;
    /* left: 700px; */
    /* left: 0; */
    /* margin-top: 25px; */
    padding: 0px 40px;
    /* border: 5px dotted rgb(197, 5, 5); */
    
}

#img-card-2{
    position: absolute;
    max-width: 190px;
    height: 216px;
    /* left: 800px; */
    /* top:750px ;*/ 
    left:1180px ;
    align-self: flex-end;
    /* border: 5px dotted rgb(197, 5, 5); */
    padding: 0px 40px;
}

#kkk{
    max-width: 570px;
    max-height: 650px; 
    /* border: 3px solid black; */
    position:relative;
}

#content_p1 {
    /* position: absolute; */
    max-width: 435px;
    max-height: 90px;
    left: 0px;
    /* top: 349px; */
    /* margin-top: 240px; */
}

#content_p2 {
    /* position: absolute; */
    max-width: 100px;
    max-height: 22px;
    align-self: center;
    /* left: 190px; */
    /* margin-top: 370px; */
    /* border: 5px dotted rgb(197, 5, 5); */
}

#content_p2 a{
    text-decoration:none;
    
}

#btn-hero{
/* position: absolute; */
max-width: 150px;
height: 52px;
/* left: 170px; */
left: 0px;
/* top: 479px; */
top: 370px;

display: flex;
flex-direction: row;
justify-content: center;
align-items: center;
/* padding: 15px 37px; */
}

.hero-content-buttons-div span{
    width: 20px;
}
.client{
     /* position: absolute; */
    max-width: 100%;
    max-height: 96px;
     margin-top: 100px;
    /* top: 226px; */
    /* border: 3px solid yellow; */
}
.sub-clients{
    /* position: absolute; */
    max-width: 1100px;
    max-height: 96px;
    margin-left:auto;
    margin-right:auto;
    /* border: 2px solid gray; */
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    /* border: 2px solid black; */
}
.sub-clients img{
    filter:grayscale();
}

.projects{
    /* position: absolute; */
    /* width: 1440px; */
    max-width: 100%;
    max-height: 561px;
    /* left: calc(50% - 1440px/2); */
    margin-top: 200px;
    /* border: 3px solid black;  */
}

.projects-container{
    /* position: absolute; */
    max-width: 1100px;
    max-height: 561px;
    margin-left: auto;
    margin-right:auto;
    /* border: 4px solid lightcoral; */

}

.projects-container-items{
    /* position: absolute; */
    max-width: 1100px;
    max-height: 444px;
    /* margin-top: 117px; */
    margin-top: 60px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
     /* border: 5px solid gray;  */
   
}

.project-item{
    /* position: absolute; */
    max-width: 330px;
    /* height: 444px; */
    /* left: 930px;
    top: 117px; */
    /* border: 2px solid salmon; */
    background: #FFFFFF;
    box-shadow: 0px 38.7755px 77.551px rgba(0, 0, 0, 0.1);
}

.project-item-text{
   
    /* border: 5px dotted rgb(197, 5, 5); */
    /* height: 194px; */
    max-width: 330px;
    /* max-height: 194px;
    max-width: 330px; */
    padding: 30px;
    box-sizing:border-box;
}


.project-item img{
    max-width: 330px;
    max-height: 240px;
    /* width: 540px; */
    /* height: 240px; */
    /* border: 2px thick red; */
}

.project-item-text-tittle{
    height: 34px;
    max-width: 270px;
    /* border: 3px solid black; */
}

.project-item-text-desc{
    height: 80px;
    max-width: 270px;
    /* border: 3px solid red; */
    /* white-space: nowrap; */
    /* overflow: hidden !important; */
    /* text-overflow:clip;
    max-width: 300px;
    max-height: 140px; */
}


.project-item-text a{
    text-decoration:none;
    color:#072AC8;
    margin-top:20px;
}

.testimonial{
    /* position: absolute; */
    max-width: 100%;
    height: 622px;
    margin-top: 200px;
    /* border: 4px solid brown; */

}
.testimonial-container{
        /* position: absolute; */
        max-width: 1320px;
        height: 622px;
        /* left: 63px; */
        /* top: 51px; */
        /* border: 2px solid white; */
        background-color: #292E47;
        margin-left: auto;
        margin-right: auto;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
}

.testimonial-flex-center{
    width: 100%;
    height: 622px;
    /* border: 3px   solid rgb(0, 225, 255); */
    display: flex;
    flex-direction: column;
    justify-content: center; 
      
    
}

.testimonial-flex-cont{
    width: 70%;
    height: 80%;
    /* border: 3px solid fuchsia; */
    margin-left: auto;
    margin-right:auto;
    display: flex;
    flex-direction: column;
    justify-content: space-between; 
    
    
}

.testimonial-flex-cont p{
    text-align: center;
    color: #FFC600;
    
}
.testimonial-flex-cont h3{
    color: white;
    margin: 0px;
}

.testimonial-flex-pics{
    width: 10%;
    /* border: 4px solid salmon; */
    display: flex;
    /* flex-wrap: wrap; */
    flex-direction: column;
    justify-content: space-between ;
   

}

.testimonial-flex-pics img{
    width: 100%;
}

.testimonial-footer{
    display:flex;
    flex-direction: row;
    justify-content: center;
}

.testimonial-footer-pic{
    width: 50px;
    border: 1px solid white;
 

}
.testimonial-footer-text{
    display:flex;
    flex-direction: column;
    justify-content: space-between;
    /* border: 1px solid red; */
}
.testimonial-footer-pic img{
    width: 50px;
}
.testimonial-footer-text p{
    margin:0px;
}
.services{
    position: absolute;
    width: 1440px;
    height: 561px;
    left: calc(50% - 1440px/2);
    top: 2881px;
}

/* #section-services{
    position: absolute;
    left: calc(50% - 1440px/2);
    top: 2881px;
} */

#section-services .ThreeColumnsSection-container-items-item img{
    width: 40px;
    height: 40px;
    margin:20px;
}

.ThreeColumnsSection{
    /* position: absolute; */
    width: 100%;
    max-height: 561px;
    /* border: 3px solid black; */
    margin-top: 200px;
}
    
.ThreeColumnsSection-container{
    /* position: absolute; */
    max-width: 1100px;
    max-height: 561px;
    margin-left: auto;
    margin-right: auto;
    /* left: 170px; */
    top: 0px;
    /* border: 3px solid gray; */
}
    
.ThreeColumnsSection-container-items{
    /* position: absolute; */
    max-width: 1100px;
    max-height: 380px;
    margin-left: auto;
    margin-top: 117px;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    /* border: 2px solid green; */
}
    
.ThreeColumnsSection-container-items-item{
        /* position: absolute; */
    max-width: 340px;
    max-height: 380px;
    /* left: 930px;
    top: 117px; */
    /* border: 2px solid salmon; */
    background: #FFFFFF;
    box-shadow: 0px 38.7755px 77.551px rgba(0, 0, 0, 0.1);
}
    
.ThreeColumnsSection-container-items-item-text{
    display:flex;
    flex-direction: column;
    /* border: 5px dotted rgb(197, 5, 5); */
    max-height: 260px;
    max-width: 340px;
    
    flex:auto;
    padding: 30px;
    box-sizing: border-box;
}

.service-item-text-tittle{
    height: 34px;
    max-width: 270px;
    /* border: 3px solid black; */
}

.service-item-text-desc{
    height: 120px;
    max-width: 270px;
    /* border: 3px solid red; */
    /* white-space: nowrap; */
    /* overflow: hidden !important; */
    /* text-overflow:clip;
    max-width: 300px;
    max-height: 140px; */
}

.service-item-text a{
    text-decoration:none;
    color:#072AC8;
    margin-top:20px;
}

.service-item-logo{
    max-width: 80px;
    height: 80px;
    margin: 40px 230px 0px 30px;
    background: #ECF7FF;
    border-radius: 49.6px;
}

.cta{
/* CTA Section */

/* position: absolute; */
width: 100%;
max-height: 500px;
margin-top: 200px;

  
}


.cta-container{
    max-width: 1320px;
    max-height: 500px;
    margin-left:auto;
    margin-right:auto;
    /* margin: 136px 110px 137px 110px; */
    /* border: 3px solid gray; */
    text-align: center;
    display: flex;
    flex-direction: column;
    justify-self: center;
    background-color: #FFC600;
  
 
}

.cta-container-content{
    max-width: 1100px;
    /* height: 227px; */
    height: 50%;
    /* margin-bottom: 5%; */
    margin-left:8%;
    margin-top:10%;
    /* box-sizing: border-box; */
    /* margin-top:5%;
    margin-left:5%;
    margin-right:5%;
    margin-bottom:5%; */
    
    /* margin: 136px 110px 137px 110px; */
    /* border: 3px solid gray; */
    text-align: center;
    display: flex;
    flex-direction: column;
    
    
    /* background-color: white; */
}

#cta_form{
    width: 100%;
    display: flex;
    flex-direction: row;
    justify-content: center;
    /* border: 3px solid green; */
    /* border: 5px dotted rgb(197, 5, 5); */
    /* justify-self:end */
    
    
}

#input_letter{
display:flex;
flex-direction: row;
max-width: 393px;
/* height: 80px; */
background-color: #FFF;


}

#letter-icon{
    /* position: absolute; */
width: 30px;
height: 30px;
/* left: 275px;
top: 172px; */
align-self: center;

}

#input_email{
/* position: absolute; */
width: 363px;
/* height: 80px; */

/* left: 245px;
top: 147px; */
box-sizing: border-box;
margin:0px;
border: 0px solid white; 

}


.btn-blue2{
    /* Auto layout */
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    padding: 1px 1px;
    
    /* position: absolute; */
  
    /* left: 1120px;
    top: 70px; */
    
    /* Primary/Default */
    background: #072AC8;
    }

.footer{
/* position: absolute; */
width: 100%;
height: 242px;
/* border: 2px solid gray; */
margin-top:200px;

}

.footer-container{
    display: flex;
    flex-direction: row;
    justify-content: space-between;

    /* position: absolute; */
    max-width: 1100px;
    height: 112px;
    margin-left: auto;
    margin-right:auto;
    /* border: 2px solid red; */
    
}
.footer img{
    width: 98.38px;
height: 30px;
}

#footer-logo-left{
    display: flex;
    flex-direction: column;
    width: 280px;
height: 108px;
/* left: 170px;
top: 30px; */
/* border: 3px solid gray; */


}

.footer-logo-left p{
/* border: 2px solid #292E47; */
margin:0px;
display:flex;
justify-self:end;

}

#footer-links{
    /* border: 2px solid green; */
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    
width: 435px;
height: 112px;

}

.footer-links-divs-pair{
    display: flex;
    flex-direction: column  ;
    /* border: 2px solid purple; */
    justify-content:space-between;

    display: flex;
  flex-wrap: wrap;
   align-content: space-between;
}

.footer-links-divs-pair p{
      margin: 0px;
      align-self: flex-end;
}

.PPageProjectSection{
    /* position: absolute; */
    max-width: 100%;
    /* height: 1181px; */
    /* left: calc(50% - 1440px/2); */
    margin-top: 10px;
    /* top: 226px; */
    /* border: 3px solid rgb(231, 35, 35);  */
}

.ProjectSection-container{
    margin-left:auto;
    margin-right:auto;
    max-width: 1100px;
    height: 100%;
    /* border: 2px solid purple; */
}
#PPageDescDiv{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}
.PPageProjectDetailsCont{
    margin-top:80px;
    /* height: 950px; */
    /* border: 2px solid orange; */
}
#PPageProjectDetailContImg{
    max-height: 440px;
    /* max-width: 1100px; */
    /* border: 2px solid black; */
}

#PPageProjectDetailContImg img{
    height: 100%;
    /* width: 100%; */
}
#PPageProjectDetailContTxt{
    margin-top:70px;
    text-align: justify;
    /* height: 420px; */
    /* border: 2px solid black; */
}

.section-contact{
    /* position: absolute; */
    max-width: 100%;
    height: 650px;
    /* left: calc(50% - 1440px/2); */
    margin-left:auto;
    margin-right:auto;
    margin-top: 98px;
    /* top: 226px; */
    /* border: 3px solid rgb(231, 35, 35);  */
}

#email-phone {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    max-width: 100%;
    /* border: 2px solid gray; */
}

#name, #email_phone,#email, #phone, #message, #btn-submit{
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    width: 100%;
    /* height: 20%; */
    /* height: 10%; */
    /* border: 2px solid gray; */
}

#message input{
    height: 100px;
    
}
.contact-form span{
    width: 10%;
}
#btn-submit{
    margin-top: 40px;
    
}
.contact-form input{
    width: 100%;
    height: 50px;
    background-color: rgba(107, 112, 141, 0.1);
    border:0px;
}
.contact-form{
    display: flex;
    flex-direction: column;
    justify-content: space-between;
           
    /* position: absolute; */
    max-width: 1100px;
    height: 650px;
    /* left: 170px; */
    /* top: 0px; */
    /* border: 5px solid orange;  */
    margin-left: auto;
    margin-right: auto;
}

@media (max-width: 480px){

.projects-container-items{
        margin-top: 60px;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
         /* border: 5px solid gray; */
}

.ThreeColumnsSection-container-items{
    margin-top: 60px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}
.sub-clients{
    display: flex;
    flex-direction: column;
    justify-content: space-between;    
}
.container{
display: flex;
flex-direction: column;
justify-content: center;
}
#img-card-1, #img-card-2 {
    display: none;

}
.cta{
    margin-top: 1000px;
}
.testimonial{
    margin-top: 1000px;
}
.hero{
    margin-top:200px
}
.client{
    margin-top:300px;
}
}

</style>
