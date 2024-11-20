<!-- ------------------------------------------ -->
<script lang="ts">
    import MyPic from '../lib/MyPic.jpg';
    import { fade, fly } from 'svelte/transition';
    import AWS from '../lib/AWS certificate.jpg';
    import Python from '../lib/Python GuviCertification.jpg';
    import Java from '../lib/Wipro certificate-.jpg'
    import PP1 from '../lib/Paper presentation.jpg'
    import PP2 from '../lib/Paper publication.jpg'
    import EE from '../lib/Email Etiquette.jpg'
    import GD from '../lib/Group disscusion_.jpg'
    import IS from '../lib/interviw skills.jpg'
    import GraphicDesign from '../lib/Intro Graphic Design.jpg'
    import PS from '../lib/Presentation Skills.jpg'
    import Python2 from '../lib/Python_page.jpg'
    import UIUX from '../lib/Ui Ux for beginners_page-0001.jpg'
	let visible = $state(false);
	// let visible = $state(true);

    setTimeout(()=>
    {
        visible = true;
    },100);
</script>

<!-- ------------------------------------------ -->
<main>
    {#if visible}
        <div class="container-fluid" in:fly={{ y: 10, duration: 2000 }} out:fade>
            <div class="row p-4 name_pic">
                <div class="col-lg-8 mt-5">
                <p class="name_font">Padma kumar <span>B.E EEE</span></p>
                <p class="email">padmakumar41759@gmail.com</p>
                
                </div>
                <div class="col-lg-4">
                <img class="my_pic" src="{MyPic}" alt="img">
                </div>
            </div>

            <div class="mt-3 p-3 Details">
                <div class="row">
                    <p class="heading">Personal Details</p>
                    <div class="details col-lg-3">
                        <b>Full Name</b>
                        <p>Padma kumar C</p>
                    </div>
                    <div class="details col-lg-3">
                        <b>Mobile number</b>
                        <p>9944035088</p>
                    </div>
                    <div class="details col-lg-3">
                        <b>DOB</b>
                        <p>23/10/2024</p>
                    </div>
                    <div class="details col-lg-3">
                        <b>Location</b>
                        <p>Udumalpet</p>
                    </div>
                </div>

                <div class="row">
                    <p class="heading">Education</p>
                    <div class="details col-lg-3">
                        <b>SSLC</b>
                        <p>SKP Matriculation & Higher Secondary School <br> 78 % </p>
                    </div>
                    <div class="details col-lg-3">
                        <b>HSC</b>
                        <p>RKR Grks Matriculation Higher Secondary School <br> 59 % </p>
                    </div>
                    <div class="details col-lg-3">
                        <b>UG</b>
                        <p>VSB College of Engineering Technical Campus  <br> 81 % ( 8.14 CGPA ) </p>
                    </div>
                    <div class="details col-lg-3">
                        <b>PG</b>
                        <p>-</p>
                    </div>
                </div>
            
                <div class="row">
                    <p class="heading">Experience</p>
                    <div class="details col-lg-12">
                        <b>Right Angle Solutions Dec 2023 - July 2024</b>
                        <p>Web & Web App Developer</p>
                    </div>
                </div>

                <div class="row">
                    <p class="heading">Skills</p>
                    <div class="details col-lg-2">
                        <p>Java</p>
                        <p>React</p>
                        <!-- <p>Rust</p> -->
                    </div>
                    <div class="details col-lg-2">
                        <!-- <p>Maven</p> -->
                        <p>Svelte</p>
                        <p>Rust</p>
                    </div>
                    <div class="details col-lg-2">
                        <!-- <p>Spring</p> -->
                        <p>Java Script</p>
                        <p>HTML</p>
                    </div>
                    <div class="details col-lg-2">
                        <p>Spring Boot</p>
                        <p>Bootstrap</p>
                    </div>
                    <div class="details col-lg-2">
                        <!-- <p>Herbinate</p> -->
                        <p>CSS</p>
                        <p>Python</p>
                    </div>
                    <div class="details col-lg-2">
                        <p>MySql</p>
                        <!-- <p>HTML</p> -->
                    </div>
                </div>
            </div>

            <div class="mt-3 p-3 Projects">
                <p class="heading skills">Projects</p>
                <div class="row">
                    <div class="col-12">
                        <p class="project">1) School Management App</p>
                        <p class="content"><b>Purpose :</b> This web application facilitates online class scheduling for tutors and allows students to view their sessions.</p>
                        <p class="content fw-bold">Key Features :</p>  
                        <ul>
                            <li>Create, manage, and view sessions.</li>
                            <li>Record attendance, track salary and bonuses for tutors.</li>
                            <li>Schedule leaves, view lessons for the day, and maintain session history.</li>
                        </ul>                          
                        <p class="content fw-bold">Technology Stack :</p>  
                        <ul>
                            <li>HTML</li>
                            <li>CSS</li>
                            <li>Bootstrap</li>
                            <li>Java Script</li>
                            <li>Type Script</li>
                            <li>Svelte</li>
                            <li>Git & Github</li>
                        </ul>                          
                    </div>
                    <div class="col-12">
                        <p class="project">2) Internal App</p>
                        <p class="content"><b>Purpose :</b> Designed for employee management, this app organizes personnel details stored in a Supabase database.</p>
                        <p class="content fw-bold">Key Features :</p>  
                        <ul>
                            <li>Leave application and tracking.</li>
                            <li>Monthly payslip downloads.</li>
                            <li>Employee detail editing.</li>
                            <li>Displays loss of pay days and remaining paid leave days.</li>
                        </ul>                          
                        <p class="content fw-bold">Technology Stack :</p>  
                        <ul>
                            <li>HTML</li>
                            <li>CSS</li>
                            <li>Bootstrap</li>
                            <li>Java Script</li>
                            <li>Type Script</li>
                            <li>Svelte</li>
                            <li>Postgres</li>
                            <li>Google Cloud Platform</li>
                            <li>Git & Github</li>
                        </ul>                          
                    </div>
                    <div class="col-12">
                        <p class="project">3) TIC-TAC-TOE</p>
                        <p><a class="project_link" href="https://tic-tac-teo-ten.vercel.app/" target="_blank">Project Link</a></p>
                        <p class="content"><b>Purpose :</b>  A fun, interactive TIC-TAC-TOE game built using Svelte.</p>                        
                        <p class="content fw-bold">Technology Stack :</p>  
                        <ul>
                            <li>HTML</li>
                            <li>CSS</li>
                            <li>Java Script</li>
                            <li>Type Script</li>
                            <li>Svelte</li>
                            <li>Git & Github</li>
                        </ul>                          
                    </div>
                    <div class="col-12">
                        <p class="project">4) Sudoku Solver</p>
                        <p><a class="project_link" href="https://github.com/Padmakumar18/Suduko-Solver/blob/main/Main.java" target="_blank">Project Link</a></p>
                        <p class="content"><b>Purpose :</b>  A unique program that solves a variation of Sudoku involving odd numbers.</p>                       
                        <p class="content fw-bold">Technology Stack :</p>  
                        <ul>
                            <li>Java with a focus on Array List</li>
                        </ul>                          
                    </div>
                </div>
            </div>

            <div class="mt-3 p-3 Certifications">
                <div class="row">
                    <p class="heading">Certifications</p>
                    <div class="details col-lg-4 mb-4">
                        <p>AWS Academy Graduate</p>
                        <img src="{AWS}" alt="">
                    </div>
                    <div class="details col-lg-4">
                        <p>Python</p>
                        <img src="{Python}" alt="">
                    </div>
                    <div class="details col-lg-4">
                        <p>Python</p>
                        <img src="{Python2}" alt="">
                    </div>
                    <div class="details col-lg-4 mb-4">
                        <p>Email Etiquette</p>
                        <img src="{EE}" alt="">
                    </div>
                    <div class="details col-lg-4">
                        <p>Group disscusion</p>
                        <img src="{GD}" alt="">
                    </div>
                    <div class="details col-lg-4">
                        <p>Interviw Skills</p>
                        <img src="{IS}" alt="">
                    </div>                    
                    <div class="details col-lg-4 mb-4">
                        <p>Presentation Skills</p>
                        <img src="{PS}" alt="">
                    </div>
                    <div class="details col-lg-4 ">
                        <p>Ui Ux for beginners</p>
                        <img src="{UIUX}" alt="">
                    </div>
                    <div class="details col-lg-4">
                        <p>Intro Graphic Design</p>
                        <img src="{GraphicDesign}" alt="">
                    </div>
                    <div class="details col-lg-4">
                        <p>Paper Presentation</p>
                        <img src="{PP1}" alt="">
                    </div>
                    <div class="details col-lg-4">
                        <p>Paper Publication</p>
                        <img src="{PP2}" alt="">
                    </div>
                    <div class="details col-lg-4">
                        <p>Java</p>
                        <img src="{Java}" alt="">
                    </div>
                </div>
            </div>

            <div class="mt-4 footer">
                <h2>Thank you</h2>
            </div>

        </div>
    {/if}
</main>
<!-- ------------------------------------------ -->

<style>
    img
    {
        width : 10em
    }
    .Details
    {
        background-color: #3d5864;
        border-radius: 1em;
        color: white;
    }

    .Projects
    {
        background-color: #e6e3da;
        border-radius: 1em;
    }

   .name_pic 
    {
        background-color: #e6e3db;
        color: #3d5864;
    }

    .Certifications
    {
        background-color: #3d5864;
        color: white;
        border-radius: 1em;
    }

    .my_pic 
    {
        width: 20em;
        height: 20em;
        object-fit: cover; 
        border-radius: 50%;
    }

    .name_font 
    {
        font-size : 5em;
    }

    .email
    {
        font-size: 2em;
    }

    .heading
    {
        font-size: 2em;
        font-weight: 600;
        color: #f5d0ad;
    }

    span
    {
        font-size: 0.4em;
    }

    .skills
    {
        color: #3d5864;
    }
    
    .project_link
    {
        text-decoration: none;
        color: white;
        background-color: #3d5864;
        padding: 0.6em;
        border-radius: 0.3em;
    }

    .content
    {
        font-size: 1.3em;
    }

    li
    {
        color:#3d5864;
    }

    .project ,.content
    {
        font-size: 1.3em;
        font-weight: 600;
        color: #3d5864;
    }

    .footer 
    {
        padding: 1em;
        text-align: center;
        background-color: #333;
        color: white;
        border-radius: 10px 10px 0px 0px ;
    }
</style>    
<!---------------------------------------------->