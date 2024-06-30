<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <title>Document</title>
    <style>
        
        body {
          font-family: Arial, sans-serif;
          margin: 0;
          padding: 0;
        }
        nav {
          background-color: #0f0202;
          overflow: hidden;
          font-size: 20px;
        }
        nav a {
          float: left;
          display: block;
          color: white;
          text-align: center;
          padding: 20px 50px;
          text-decoration: none;
        }
        nav a:hover {
          background-color: #ddd;
          color: black;
        }
        .login-button {
          float: right;
        }
        .sigh_up {
                  float: right;
                  display="block";

        }
        .sigh_up:hover {
                 
            color: rgb(12, 12, 11);
        }
              .sectionimg {
                
                height: 100%;
                width: 100%;
                
              }
              .texts {
                        position: absolute;
                        top: 50%;
                        left: 70%;
                        transform: translate(-50%, -50%);
                        color: white;
                        text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
              }
              .button {
                background-color: #6F42C1; 
                cursor: pointer;
                border: none;
                font-size: 25px;
                transition: all 0.5s;
                border-radius: 80px;
                color: white;
                text-align: center;
                padding: 14px 20px;
                text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
              }
              .button span {
                 cursor: pointer;
                 display: inline-block;
                 position: relative;
                  transition: 0.5s;
}

            .button span:after {
               content: '\00bb';
               position: absolute;
               opacity: 0;
               top: 0;
               right: -20px;
               transition: 0.5s;
                }

            .button:hover span {
             padding-right: 25px;
}

             .button:hover span:after {
               opacity: 1;
                right: 0;
                }
             .button:hover {
                 background-color: orange;
                  }
                  .footer {
                     background-color: #333;
                     color: white;
                     padding: 20px 0;
                     margin-top: auto;
                       }  
                       .footer-container {
                     display: flex;
                     justify-content: space-around;
                     flex-wrap: wrap;
                     max-width: 1200px;
                     margin: 0 auto;
                     padding: 0 20px;
                     text-decoration: none;
} 
                 .footer-section {
                           flex: 1;
                           min-width: 200px;
                           margin: 10px 0;
                           
                           } 
                           .social-link { 
                            color: white;
                            text-decoration: none;

                           }
                           .footer-link {
                                  color: white;
                                  text-decoration: none;
                           }
                           .footer-bottom {
                            text-align: center;
                            padding: 10px 0;
                            border-top: 1px solid #444;
                            margin-top: 20px;
                           
                            
                           }
                           
                        .card-container {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    max-width: 1500px;
    gap: 20px;
}

.card {
    background-color: white;
    border: 1px solid #ddd;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    overflow: hidden;
    width: 300px;
    transition: transform 0.3s ease;
    cursor: pointer;
}

.card:hover {
    transform: scale(1.05);
}

.card-image img {
    width: 100%;
   
}

.card-content {
    padding: 15px;
}

.card-title {
    margin: 0;
    font-size: 18px;
    margin-bottom: 10px;
}

.card-description {
    margin: 0;
    font-size: 14px;
    color: #666;
}

.card-footer {
    padding: 15px;
    text-align: center;
}

.card-button {
    padding: 10px 20px;
    background-color: #007BFF;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.card-button:hover {
    background-color: #0056b3;
}
        .section-2 {
               height: 30%;
               width: 30%;
               border-radius: 80%;
               padding: 10px 20px;

        } 
        .section-2h1{
            display: flex;
            text-align: center;
            margin: 50px;
            
        }
        
        
          .heading {
            position: absolute;
            left: 55%;
            font-size: 50px;
            
            
            
          }
          .ipsum{
             
            padding: 10px 20px;
            text-align: center;
            margin-top: 95px;
            
          }
          .section-3 {
            border-radius: 8%;
              height: 20%;
              width: 30% ;
              display: block;
              margin: 10px 10px;
              float: right;
              
             
                            
          }
          .image-6 {
            overflow: hidden;
            position: relative;
             
            padding: 10px 40px;
             
            
          }
           .about-1 {
             
            text-align: center;
           }
         .paragraph-1 {
            
            text-align: center;
         }
            
                  
          
      </style>
</head>
<body>
    <nav>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#products">Categories</a>
        <a href="#contact">Contact Us</a>
        <a href="#login" class="login-button">Login</a>
        <a href="#" class="sigh_up">Sigh up</a>
      </nav>


      <section >
        <div class="texts">
            <h1>"Welcome to our world of style and elegance, where every accessory tells a story."</h1>
            <h2>Join us on a journey where accessories transform ordinary into extraordinary. Shop now and redefine your fashion narrative.</h2>
            <button class="button"><span>Shop Now</span></button>
         </div>
        <div >
            <img src="C:\Users\dell\Downloads\fashion.jpg" alt="Description of your image" class="sectionimg">
        </div>

        
        
      </section>

      
        <div class="card-container">
            <div class="card">
                <div class="card-image">
                    <img src="C:\Users\dell\Downloads\fashion1.jpg" alt="Card Image 1">
                </div>
                <div class="card-content">
                    <h3 class="card-title">Card Title 1</h3>
                    <p class="card-description">This is a brief description of the card content.</p>
                </div>
                <div class="card-footer">
                    <button class="card-button">Learn More</button>
                </div>
            </div>
            <div class="card">
                <div class="card-image">
                    <img src="C:\Users\dell\Downloads\shoes.jpg" alt="Card Image 2">
                </div>
                <div class="card-content">
                    <h3 class="card-title">Card Title 2</h3>
                    <p class="card-description">This is a brief description of the card content.</p>
                </div>
                <div class="card-footer">
                    <button class="card-button">Learn More</button>
                </div>
            </div>
            <div class="card">
                <div class="card-image">
                    <img src="C:\Users\dell\Downloads\watch.jpg" alt="Card Image 3">
                </div>
                <div class="card-content">
                    <h3 class="card-title">Card Title 3</h3>
                    <p class="card-description">This is a brief description of the card content.</p>
                </div>
                <div class="card-footer">
                    <button class="card-button">Learn More</button>
                </div>
            </div>
        </div>
        <div class="section-2h1"  >
            <img src="C:\Users\dell\Downloads\sunglass.jpg" alt="Card Image 3" class="section-2">
            <h1 class="heading">About Us</h1>
            <p class="ipsum"> 
                Why do we use it?
                It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still in their infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose (injected humour and the like).
              Where does it come from?
                Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old. Richard McClintock, a Latin professor at Hampden-Sydney College in Virginia, looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, and going through the cites of the word in classical literature, discovered the undoubtable source. Lorem Ipsum comes from sections 1.10.32 and 1.10.33 of "de Finibus Bonorum et Malorum" (The Extremes of Good and Evil) by Cicero, written in 45 BC.
                </p>
        </div>
        <div class="image-6">
            <img src="C:\Users\dell\Downloads\fashion2.jpg" alt="Card Image 3" class="section-3">
            <h1  class="about-1">About Us</h1>
            <p class="paragraph-1">
                Why do we use it? It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover many web sites still in their infancy. Various versions have evolved over the years, sometimes by accident, sometimes on purpose (injected humour and the like). Where does it come from? Contrary to popular belief, Lorem Ipsum is not simply random text. It has roots in a piece of classical Latin literature from 45 BC, making it over 2000 years old. Richard McClintock, a Latin professor at Hampden-Sydney College in Virginia, looked up one of the more obscure Latin words, consectetur, from a Lorem Ipsum passage, and going through the cites of the word in classical literature, discovered the undoubtable source. Lorem Ipsum comes from sections 1.10.32 and 1.10.33 of "de Finibus Bonorum et Malorum" (The Extremes of Good and Evil) by Cicero, written in 45 BC.
            </p> 
            <p> Why do we use it? It is a long established fact that a reader will be dis
                Why do we use it? It is a long established fact that a reader will be dis
                Why do we use it? It is a long established fact that a reader will be dis
                Why do we use it? It is a long established fact that a reader will be dis
                Why do we use it? It is a long established fact that a reader will be distracted by the 
            </p>
            <p>Why do we use it? It is a long established fact that a reader will be distracted by the 
                Why do we use it? It is a long established fact that a reader will be distracted by the 
                Why do we use it? It is a long established fact that a reader will be distracted by the 
                Why do we use it? It is a long established fact that a reader will be distracted by the 
                Why do we use it? It is a long established fact that a reader will be distracted by the 
            </p>
        </div>
        <div class="row-container">
            <div class="row" >
              <div class="col" id="col2">
                <img src="C:\Users\dell\Downloads\fashion1.jpg" alt="Card Image 1"  height="100%" width="100%" >
              </div>
              <div class="col"  id="col2">
                <img src="C:\Users\dell\Downloads\fashion1.jpg" alt="Card Image 1" height="100%" width="100%">
              </div>
              <div class="col"id="col2" >
                <img src="C:\Users\dell\Downloads\fashion1.jpg" alt="Card Image 1"height="100%" width="100%" >
              </div>
            </div>
          </div>
         
    <footer class="footer">
        <div class="footer-container">
            <div class="footer-section">
                <h3>Contact Us</h3>
                <p>Email: info@example.com</p>
                <p>Phone: (123) 456-7890</p>
            </div>
            <div class="footer-section">
                <h3>Follow Us</h3>
                <a href="#" class="social-link">Facebook</a>
                <a href="#" class="social-link">Twitter</a>
                <a href="#" class="social-link">Instagram</a>
            </div>
            <div class="footer-section">
                <h3>Useful Links</h3>
                <a href="#" class="footer-link">Privacy Policy</a>
                <a href="#" class="footer-link">Terms of Service</a>
                <a href="#" class="footer-link">FAQ</a>
            </div>
        </div class="image-6">
        
            <p class="footer-bottom" >&copy; 2024 Your Company. All rights reserved.</p>
        
    </footer>
    
</body>
</html>
