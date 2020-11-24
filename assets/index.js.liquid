
  function closeNav() {
    document.getElementById("myNav").style.width = "0%";
    document.getElementById("overallbody").style.height = "0%";
    document.body.style.position = "relative";
  }
var slider_container =document.querySelectorAll('sixteen_collection_container');
var sliders =document.querySelectorAll('.sixten_slider');
var arrowLeft =document.getElementsByClassName('prev')
console.log(arrowLeft)

function reset(){
  for(var i=0; i>sliders.length;i++){
    console.log(sliders)
    sliders[i].style.display="none"
  }
}

function moveImage(){
  reset()

}

moveImage()
  
 function openNav() {
    document.getElementById("myNav").style.width = "60%";
    document.getElementById("overallbody").style.height = "100%";
    document.body.style.position = "fixed";
   
  }
  
  /* Close when someone clicks on the "x" symbol inside the overlay */


  
  // JavaScript Document
  "use strict";
  let item = document.getElementsByClassName("slide");
  let slider = document.getElementsByClassName("sliders");
  console.log(slider)
  
  let position = 0; //slider postion
  productScroll();
  
  function productScroll() {
    let prev = document.getElementsByClassName("pro-prev");
    let next = document.getElementsByClassName("pro-next");
  
 for(var x=0; x<item.length;x++){
   var allItem =item[x]
   console.log(allItem)
 }

 for(let b=0;b<prev.length;b++){
  prev[b].addEventListener("click", function() {
    //click previos button
    if (position >0) {
      //avoid slide left beyond the first item
    
      position -= 1;
      
      translateX(position); //translate items
    }
  });  

}

    for (let i = 0; i < next.length; i++) {
      //refer elements by class name
      next[i].addEventListener("click", function() {
        if (position >= 0 && position < hiddenItems()) {
          //avoid slide right beyond the last item
          
          position += 1;
          translateX(position); //translate items
        }
      });
    }

   
    
  
    function hiddenItems() {
      //get hidden items
      let items = getCount(allItem, false);
      for(var x =0; x<slider.length;x++){

        var visibleItems = slider[x].offsetWidth / 210;
        console.log(visibleItems)
        return items - Math.ceil(visibleItems);
      }
     
    }
  }
  
  function translateX(position) {
    //translate items
 console.log(position)
    for(var p =0;p<item.length;p++){
      item[p].style.left = position *-230 + "px";
      console.log(p)
        }
        

      
  }
  
  function getCount(parent, getChildrensChildren) {
    //count no of items
    let relevantChildren = 0;
    let children = parent.childNodes.length;
    for (let i = 0; i <children; i++) {
      console.log(children)
      if (parent.childNodes[i].nodeType != 3) {
        if (getChildrensChildren)
          relevantChildren += getCount(parent.childNodes[i], true);
        relevantChildren++;
      }
    }
    return relevantChildren;
  }
 // init controller
 let homeController = new ScrollMagic.Controller();
 const HeaderTl =gsap.timeline();
  
  HeaderTl
  .fromTo("#header_bar",
    {
  opacity:0,
  x:-200,
  ease:"back",
   
   
  },
  {
    duration:1.5,
    opacity:1,
    x:0
  }
  )
 
  const offTl =gsap.timeline();
  offTl
  .fromTo(".off-sale-text",
  {
  
  opacity:0,
  x:-200,
 
  },
  {
    opacity:1,
    x:0,
    duration:1.5,
   

  },
// ">-1.5"
  )
    const newTl =gsap.timeline();
    newTl
  .fromTo(".New_arrival_text",
  {
  x:-100,
  opacity:0,

 
 
  },
  {
    x:0,
    opacity:1,
    duration:1.5,
  },
 
  )
  
  .fromTo(".New_arrival_image",
  {
 y:135,
  opacity:0,
  },
  { 
    y:0,
    opacity:1,
    duration:1.5,
  },
 ">-1"
  )
  let fourCollectionsNode =document.querySelectorAll(".four_collections")
  if(fourCollectionsNode != null){
    console.log(fourCollectionsNode)
    fourCollectionsNode.forEach((node)=>{
      let fourCollectionsTL = gsap.timeline();
      fourCollectionsTL.fromTo(
       node.querySelectorAll( ".four_collections .col-md-3"),
        {
          opacity: 0,
          y: 100,
        },
        {

          opacity: 1,
          y: 0,
          stagger: 0.3,
          duration: 0.4,
        },
       
      );
      let four_collections = new ScrollMagic.Scene({
        triggerElement: ".four_collections",
        triggerHook: 0.20,
        reverse: true,
        offset: 20,
        duration: 0,
      })
      .setTween(fourCollectionsTL)
      // .addIndicators()
      .addTo(homeController);
      
    })

  }

  const footerTl = gsap.timeline();
  footerTl.fromTo(
    ".footer-fade-in",
    {
      opacity: 0,
      y: 100,
    },
    {
      opacity: 1,
      y: 0,
      stagger: 0.3,
      duration: 0.4,
    }
  );


let newArrival = new ScrollMagic.Scene({
  triggerElement: ".off-sale-text",
  triggerHook: .20,
  reverse: true,
  offset: 100,
  duration: 0,
})
.setTween(newTl)
// .addIndicators()
.addTo(homeController);



let footer = new ScrollMagic.Scene({
  triggerElement: ".newsletter",
  triggerHook: 0.20,
  reverse: true,
  offset: 100,
  duration: 0,
})
.setTween(footerTl)
.addIndicators()
.addTo(homeController);