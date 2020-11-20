# bootstrap
basics of butttons &amp; jumbotron
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title></title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css" integrity="sha384-TX8t27EcRE3e/ihU7zmQxVncDAy5uIKz4rEkgIXeMed4M0jlfIDPvg6uqKI2xXr2" crossorigin="anonymous">

  </head>
  <body>
    <h1>Bootstrap!</h1>
    <div class="container">
    <h1>Hello World!</h1> <!--notice how inside container class everything is contained & distant from left margin*/ -->
     <button  class="btn btn-success btn-lg" type="button" name="button">I am on:</button>
     <button  class="btn btn-success btn-lg" disabled="disabled" type="button" name="button">I am of:</button>
    </div>

    <p>now lets see jumbotrons</p>
    <p>I am a normal jumbotron</p>
    <div class="jumbotron">
  <h1 class="display-4">Hello, world!</h1>
  <p class="lead">This is a simple hero unit, a simple jumbotron-style component for calling extra attention to featured content or information.</p>
  <hr class="my-4">
  <p>It uses utility classes for typography and spacing to space content out within the larger container.</p>
  <a class="btn btn-primary btn-lg" href="#" role="button">Learn more</a>
</div>
 <p>I am a jumbotron that is going to be inside a container class.</p>
 <div class="container">
   <div class="jumbotron">
  <h1 class="display-4">Hello, world!</h1>
  <p class="lead">This is a simple hero unit, a simple jumbotron-style component for calling extra attention to featured content or information.</p>
  <hr class="my-4">
  <p>It uses utility classes for typography and spacing to space content out within the larger container.</p>
  <a class="btn btn-primary btn-lg" href="#" role="button">Learn more</a>
</div>
 </div>
  </body>
</html>
