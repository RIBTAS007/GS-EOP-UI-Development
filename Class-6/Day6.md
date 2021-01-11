# Day 6 - Making a Web Resume

Mentored by : [Ritika Gupta](https://www.linkedin.com/in/gritika1906/)

Platforms used : [jsfiddle](https://jsfiddle.net/) and [codepen.io](https://codepen.io/collection/AQPkmq )

## [Click here to watch the demo](https://ribtas007.github.io/GS-EOP-UI-Development/Class-6/index.html)
           
## HTML Code

```HTML

<html>
    <head>
        <title>Resume</title>
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/fontawesome/4.7.0/css/font-awesome.min.css">
    </head>
    
    <body>
        <header>
            <div>
                <img src="https://itibalasore.org/wpcontent/uploads/2018/02/default-user-male.png" />
            </div>
            <div>
                <span>
                    Email:
                    <a href="mailto: abc@xyz.com">abc@xyz.com</a>
                </span>
                <span>
                    Contact:
                    <a href="tel:9999999999">9999999999</a>
                </span>
                <span>
                    Address:
                    #999 abc street, xyz colony, city - pincode
                </span>
            </div>
        </header>
        <main>
            <aside>
                <h2>
                   Skills
                </h2>
                <span>
                    HTML
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                </span>
                <span>
                    CSS
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                </span>
                <span>
                    SASS
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star-half-o"></i>
                </span>
                <h2>
                    Languages
                </h2>
                <p>
                    English
                </p>
                <span class="lang-param">
                    Read
                    <i class="fa fa-check-square"></i>
                </span>
                <span class="lang-param">
                    Write
                    <i class="fa fa-check-square"></i>
                </span>
                <span class="lang-param">
                    Speak
                    <i class="fa fa-check-square"></i>
                </span>
                <p>
                    Hindi
                </p>
                <span class="lang-param">
                    Read
                    <i class="fa fa-check-square"></i>
                </span>
                <span class="lang-param">
                    Write
                    <i class="fa fa-check-square"></i>
                </span>
                <span class="lang-param">
                    Speak
                    <i class="fa fa-check-square"></i>
                </span>
            </aside>
            <article>
                <h2>
                     summary
                </h2>
                <p>
                    I am user interface developer with an experience of 3.5 years into the software development industry. I have a  strong grip on tech stack like HTML, CSS, SASS preprocessor,Bootstrap, Responsive Web Designing. I have worked an coordinated with the team through some platforms like Git task versioning, developer tools etc.
                </p>
                <h2 class="profession-head">
                    Professional Experience
                </h2>
                <p>
                    <span class="head">cognizant Technology Solutions,
                        Hyderabad
                    </span>
                    <span>
                        I have worked with CTS for 2 years from 2012-2016 in User interface development department on a project called meeting organizer.
                    </span>
                    <span class="head">
                        Exzeo India Pvt Ltd</span>
                    <span>
                        I have worked with Exzeo for a span of 9 months into core user interface development and designing team for creating prototypes of the products.
                    </span>
                </p>
                    <h2 class="education-head">
                        Educational Qualifications
                    </h2>
                <p>
                    <span class="head">Chandigarh Group Of Colleges,
                        Mohali
                    </span>
                    <span>
                        I have graduated with a degree of B.Tech in Computer Science engineering, batch 2016 with overall percentage of 85%.
                    </span>
                    <span class="head">
                        D.A.V Public School, Ludhiana
                    </span>
                    <span>
                        I have studied Non-medical and regular subjects of studies from this insitution and passed my higher secondary and senior secondary exams with a percentage which is 90%+.
                    </span>
                </p>
                <h2 class="certification-head">
                     Certifications
                </h2>
                <p>
                    <span class="head">
                        LinkedIn HTML Learning
                    </span>
                    <span>
                        I have learnt fundamentals of coding with HTML language and creating basic layouts for web pages using HTML tags, attributes and their values.
                    </span>
                </p>
            </article>
        </main>
        <footer>
            <p>
                <span>
                    LinkedIn Url:
                </span>
                <a href="https://linkedin.com/">My LinkedIn Profile</a>
            </p>
            <p>
                <span>
                    Portfolio Link:
                </span>
                <span>
                    <a href="https://codepen.io/">My Codepen portfolio</a>
                </span>
            </p>
            <p>
                <span>Web Resume:</span>
                <a href="https://codepen.io/resume">My Web based Resume</a>
            </p>
        </footer>
    </body>
</html>

```
## SCSS Code

``` CSS
*{
    margin: 0;
    padding: 0;
    font-family: Segoe UI, helvetica, sans-serif;
    color: brown;
}

header{
    display: flex;
    justify-content: space-between;
    background-color: beige;
    padding: 12px;
    img{
        width: 50px;
        height: 50px;
        border-radius: 50%;
    }
    span{
        display: block;
        a{
            text-decoration: none;
            margin-left: 10px;
        }
    }
}

main{
    display: flex;
    justify-content: space-between;
    aside{
        background-color: goldenrod;
        padding: 34px;
        min-width: 200px;
        h2{
            text-transform: capitalize;
            margin-bottom: 12px;
            margin-top: 16px;
        }
        span{
            display: block;
            margin-bottom: 10px;
            &.lang-param{
                display: inline-block;
                margin-right: 5px;
            }
        }
        p{
            font-weight: 600;
        }
    }
    article{
        padding: 24px;
        h2{
            text-transform: capitalize;
            margin-bottom: 12px;
            margin-top: 16px;
            &.profession-head{
               &::after{
                   content: "\f0b1";
                   font-family: FontAwesome;
               }
            }
            &.education-head{
                &::after{
                    content: "\f19d";
                    font-family: FontAwesome;
                }
            }
            &.certification-head{
                &::after{
                    content: "\f0a3";
                    font-family: FontAwesome;
                }
            }
        }
        span.head{
            font-weight: 700;
            display: block;
            margin-bottom: 8px;
            margin-top: 12px;
            text-transform: capitalize;
        }
    }
}
footer{
    background-color: beige;
    text-align: center;
    padding: 12px;
    a{
        text-decoration: none;
        margin-left: 10px;
    }
}
```
