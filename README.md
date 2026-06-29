বুকমার্কলেট কোড:


কোডটি কপি করে আপনার আগের বুকমার্কটির URL বক্সে পেস্ট করে সেভ করুন:
javascript:(function(){var el=document.querySelectorAll('input,textarea');for(var i=0;i<el.length;i++){el[i].onpaste=null;el[i].oncopy=null;el[i].oncut=null;el[i].oncontextmenu=null;el[i].removeAttribute('onpaste');el[i].removeAttribute('oncopy');el[i].removeAttribute('oncut');el[i].removeAttribute('oncontextmenu');el[i].style.userSelect='auto';}})();


ব্যবহার: ভিসা আবেদনের যে পেজে ইমেইল বক্স আছে, সেখানে গিয়ে শুধু বুকমার্কটিতে একবার ক্লিক করবেন। এরপর সাথে সাথেই আপনি সাধারণ নিয়মে Ctrl+V বা মাউসের রাইট ক্লিক ব্যবহার করে পেস্ট করতে পারবেন।
