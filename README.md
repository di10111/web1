
<!DOCTYPE html>
<html lang="en" dir="ltr">

<head>
  <meta charset="utf-8">
  <title></title>
  <style media="screen">
    #def {
      background-color: orange;
      color: yellow;
opacity: 0.5;
font-size: 25px;
}
</style>
</head>

<body>
  <h1 class="h333">안녕하세요</h1>
  <h2 class="h333">저의 이름은</h2>
  <h3 class="h333">이연주입니다</h3>
  <h3 class="h333">이연주입니다2</h3>
  <h3 class="h333">이연주입니다3</h3>
</body>
<script type="text/javascript">
  var tag = document.getElementsByClassName('h333');
  tag[0].addEventListener("mouseover", function() {
    tag[0].id = "def";
    tag[1].id = "def";
    tag[2].id = "def";
    tag[3].id = "def";
    tag[4].id = "def";
    console.log();
  });
tag[1].addEventListener("click", function()
{
  alert('두번째 버튼을 클릭 하셨습니다.');
});
  //h3[2].addEventListener("click", ddd);

  //function ddd() {
    //h3[1].style.color = 'red';
    //h3[1].style.backgroundColor = 'black';}
</script>
</html>
