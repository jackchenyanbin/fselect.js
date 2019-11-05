# fselect.js 依赖jquery

1、用法
 普通初始化 
 $(id).fselect();
 动态初始化
  if($(id).parent().hasClass('fs-wrap')){
      $(id).fSelect('reload',{showSearch:false});
  }else{
      $(id).fSelect();
  }
  
  我主修后端，前端只做了解，有问题QQ:1094344859
