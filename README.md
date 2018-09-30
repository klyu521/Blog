## Homework 

### Step 1: Install Git, Create an account on Github, and create a repository for the class.
First I open the Git Bash and creat the floder, then I create your my repository. And I Try to push the README.md to remote origin.

```bash
mkdir klyu521.github.io
cd klyu521.github.io
echo "klyu521.github.io" >> README.md
git init
git confic --global user.name "klyu521"
git config --global user.email "klyu16@wou.edu"
git remote add origin https://github.com/klyu521/klyu521.github.io.git
git add README.md
git commit -m "first commit."
git push -u origin master
```

### Step 2:Using HTML to do my home page.
In this step I try to use Bootstrap, and I visit http://getbootstrap.com/ to learn how to use it.
First I do the homepage for this class.

```bash
<!DOCTYPE html>
<!--my HOMEWORKS page. -->
<html lang="en">
    <head>
        <title>Kaimeng Lyu</title>
            <!-- Required meta tags -->
            <meta charset="utf-8">
            <meta name="viewport" content="width=device-width, initial-scale=1">

            <!--Bootstrap CSS-->
            <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
            <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
            <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
    </head>

    <body style="background-color:yellow">
        <h1 class="text-center">Kaimeng Lyu</h1>
        <div class="container">
          <p class="text-center">
                  I am from Chinese, and this is my last year in Western Oregon University. I hope I can do my best in this course.
                  <br>My email address is klyu16@wou.edu

                  </address>

           <hr>
            <h2 class="text-center">CS460 HOMEWORKS</h2>

                <p class="text-center">
                    This is my page for the CS460. I list my homeworks in this page.
                </p>
                <hr>

                <h3 class="text-center">
                    The projects for this class are documented on the following page: <br>

                    <a href=./README.md>HW1 BLOG</a>
                    <br>
                    <a href=./cs460/hw1/hw1.html>HW1 DEMO</a>
                </h3>
        </div>
    </body>
    ```
    # Then I start doing my own website, it is a brand website.
    At first I do the navigation bar, it will be 4 pages in my website.
    ```bash
      <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-dark">
       <a class="navbar-brand" img src="https://designdough.co.uk/wp-content/uploads/2018/04/Supreme-logo-newyork-1920x1080.jpg" href="hw1.html">Supreme</a>
       <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarsExampleDefault" aria-controls="navbarsExampleDefault" aria-expanded="false" aria-label="Toggle navigation">
         <span class="navbar-toggler-icon"></span>
       </button>

       <div class="collapse navbar-collapse" id="navbarsExampleDefault">
         <ul class="navbar-nav mr-auto">
           <li class="nav-item active">
             <a class="nav-link" href="Hoodie.html">Hoodie <span class="sr-only">(current)</span></a>
           </li>
           <li class="nav-item">
             <a class="nav-link" href="Shirts.html">Shirts</a>
           </li>
           <li class="nav-item">
             <a class="nav-link disabled" href="Contact us.html">Contact us</a>
           </li>

         </ul>
         <form class="form-inline my-2 my-lg-0">
           <input class="form-control mr-sm-2" type="text" placeholder="Search" aria-label="Search">
           <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
         </form>
       </div>
     </nav>
    ```
   # Next I do the list and table.
    ```bash
    div class="row">
         <div class="col-md-4">
             <dl>
                 <dt>Hoodie</dt>

                 <dd>-Prices
                     <ul>
                       <li>Box logo - $225</li>
                       <li>Baisc - $135</li>
                       <li>Other - $150</li>
                     </ul>
                 </dd>
             </dl>
         </div>
         <br>
         <br>
         <br>
         <div class="col-md-4">
              <dl>
                 <dt>Shirts</dt>

                 <dd>- Prices
                     <ul>
                         <li>Box logo - $100</li>
                         <li>Baisc - $55</li>
                         <li>Other - $70</li>
                     </ul>
                 </dd>
             </dl>
         </div>
        <br>
        <br>
        <br>
         <div class="col-md-4">
              <dl>
                 <dt>Shorts</dt>

                 <dd>- Prices
                     <ul>
                       <li>Box logo - $150</li>
                       <li>Baisc - $110</li>
                       <li>Other - $120</li>
                     </ul>
                 </dd>
             </dl>
         </div>
         <br>
         <br>
         <br>
         <br>
         <br>
         <br>
    <div class="col-md-4">
        <img class="img-responsive" src="image/logo.jpg.jpg"  >
    </div>
```

```bash
<div class="pagebackground">
            <div class="container">
                <div class="content">
                   <h2>Contact us / Contact</h2>
                   <table class="table table-striped">
                       <tbody>
                           <tr>
                               <td>Facebook</td>
                               <td><a href="https://www.facebook.com/Supreme/">https://www.facebook.com/klyu/</a></td>
                           </tr>
                           <tr>
                               <td>Wechat</td>
                               <td><a href="864488590">864488590</a></td>
                           </tr>
                           <tr>
                               <td>Instagram</td>
                               <td><a href="https://www.instagram.com/Supreme/">https://www.instagram.com/klyu/</a></td>
                           </tr>
                           <tr>
                               <td>Email</td>
                               <td>klyu16@wou.edu</td>
                           </tr>
                       </tbody>
                   </table>
                </div>
           </div>
       </div>
 ```
 # At last I use CSS to modify my pages.
