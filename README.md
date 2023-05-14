- 👋 Hi, I’m @eyeeed
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
var myStorage = window.localStorage, pageCount;
window.addEventListener('load', function(){
   if(!myStorage.getItem("pageCount")){
      myStorage.setItem('pageCount', 1);
   } else {
      pageCount = myStorage.getItem("pageCount");
      pageCount = pageCount + 1;
      myStorage.setItem('pageCount', pageCount );
   }
   console.log('page view count', myStorage.getItem("pageCount"));
});
<!---
eyeeed/eyeeed is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
