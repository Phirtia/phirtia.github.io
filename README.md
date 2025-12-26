<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Phirtia Silva | Portfolio</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 50px 0;
        }

        h1, h2 {
            color: #111;
        }

        a {
            color: #1a73e8;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        /* About the CEO */
        #about-ceo p {
            margin-bottom: 20px;
            line-height: 1.7;
        }

        /* Portfolio section */
        #portfolio {
            background-color: #ffffff;
            padding: 50px 0;
        }

        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 30px;
        }

        .project-card {
            background-color: #f0f4f8;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            overflow: hidden;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.2);
        }

        .project-card img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }

        .project-content {
            padding: 20px;
        }

        .project-content h3 {
            margin-top: 0;
            margin-bottom: 10px;
            font-size: 1.2em;
        }

        .project-content p {
            font-size: 0.95em;
            margin-bottom: 15px;
        }

        .project-content a {
            font-weight: bold;
        }

        @media(max-width: 768px) {
            .projects {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>

    <!-- About the CEO Section -->
    <section id="about-ceo" class="container">
    <div style="flex: 1; min-width: 250px;">
        <img src="IMG_4650.JPG" alt="Phirtia Silva" style="width: 100%; border-radius: 12px;">
    </div>
        <h1>About the CEO</h1>
        <p><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/phirtia-silva" target="_blank">Phirtia Silva</a></p>
        <p>Phirtia Silva is a Brazilian social and data scientist with a remarkable track record in public policy analysis, human rights, and digital transformation. She is the founder of D3S Consultoria, a nonprofit organization that promotes social impact across Brazil and Latin America through data-driven strategies and the use of social impact technologies within the Third Sector.</p>

        <p>Throughout her career, Phirtia has worked across the public, private, nonprofit, and international sectors, contributing her expertise to high-impact projects on topics such as migration and refuge, LGBTQIAPN+ rights, child and youth protection, gender-based violence, and human trafficking—as well as various issues related to markets, industry, and consumer behavior.</p>

        <p>Her approach combines rigorous data analysis with a deep understanding of social structures and community needs. A Social Sciences graduate, with a specialization in Data Science, Phirtia is currently pursuing a Master’s in Data Science for Public Policy at the London School of Economics. Her work has received both national and international recognition, and she is widely respected for her ability to transform complex realities into actionable insights that shape inclusive and equitable public policies.</p>

        <p>At the heart of her work lies a simple belief: data can, and should, be used as a force for justice and systemic change.</p>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio">
        <div class="container">
            <h2>Portfolio</h2>
            <div class="projects">

                <!-- Project 1 -->
                <div class="project-card">
                    <img src="2.png" alt="Predictive Model">
                    <div class="project-content">
                        <h3>Governo | Government - Predictive Model</h3>
                        <p>Applying clustering and logistic regression techniques to predict the likelihood of re-victimization, return, or non-return to services dedicated to the protection of women victims of domestic violence and offered by the Municipal Secretariat for Human Rights and Citizenship of Sao Paulo.</p>
                        <a href="#">Read More</a>
                    </div>
                </div>

                <!-- Project 2 -->
                <div class="project-card">
                    <img src="1.png" alt="Customer Segmentation">
                    <div class="project-content">
                        <h3>Tech NGO - Customer Segmentation</h3>
                        <p>Segmentation to capture different audience profiles, service needs, and to develop better communication, advocacy, and continuity strategies. Use of K-prototypes: an algorithm that considers both quantitative and qualitative data for clustering.</p>
                        <p><strong>Confidential</strong></p>
                    </div>
                </div>

                <!-- Project 3 -->
                <div class="project-card">
                    <img src="4.png" alt="Descriptive Analysis">
                    <div class="project-content">
                        <h3>Human Rights NGO - Descriptive Analysis in a Complex Context</h3>
                        <p>Database analysis on victims of human trafficking for the purpose of forced criminality, including sensitive variables such as nationality, race/ethnicity, and human rights violations.</p>
                        <a href="#">Read More</a>
                    </div>
                </div>

                <!-- Project 4 -->
                <div class="project-card">
                    <img src="3.png" alt="Priority Matrix">
                    <div class="project-content">
                        <h3>Private Company - Priority Matrix</h3>
                        <p>Development of a Priority Matrix based on NPS survey data for a major industrial company, aiming to identify key areas for improvement and guide strategic decision-making. The analysis supported prioritization of customer pain points and aligned initiatives with user satisfaction and business impact.</p>
                        <p><strong>Confidential</strong></p>
                    </div>
                </div>

                <!-- Project 5 -->
                <div class="project-card">
                    <img src="5.png" alt="Geoprocessing">
                    <div class="project-content">
                        <h3>Governo | Government - Geoprocessing of spatial and geographic data</h3>
                        <p>Conducted a geoterritorial study to identify the optimal location for implementing a new facility of the Municipal Secretariat for Human Rights and Citizenship, aimed at serving the LGBTQIA+ population in the city of São Paulo. The analysis combined spatial, demographic, and social vulnerability data to support inclusive and equitable public policy planning.</p>
                        <a href="#">Read More</a>
                    </div>
                </div>

                <!-- Project 6 -->
                <div class="project-card">
                    <img src="6.png" alt="Text Mining">
                    <div class="project-content">
                        <h3>Environmental NGO - Text Mining and Social Listening</h3>
                        <p>Performed social listening and text mining analysis for an NGO handling 50,000 annual cases focused on socio-environmental issues across Brazil. The study leveraged large-scale data from social media and client feedback to identify key trends, public sentiment, and emerging concerns, enabling the organization to tailor its strategies and improve community engagement nationwide.</p>
                        <p><strong>Confidential</strong></p>
                    </div>
                </div>

                <!-- Project 7 -->
                <div class="project-card">
                    <img src="7.png" alt="General Analysis Expertise">
                    <div class="project-content">
                        <h3>Research Institutes - General Analysis Expertise</h3>
                        <p>Plan and coordinate quantitative and qualitative research projects, including the design and production of questionnaires, data tabulation, and index development. In-depth data analysis, UX/CX/BI experience, focus groups. Topics include illegal or irregular water use in favelas, electric vehicles, ESG indicators, KPI development, and studies across service/product sectors.</p>
                        <p><strong>Several Sources</strong></p>
                    </div>
                </div>

                <!-- Project 8 -->
                <div class="project-card">
                    <img src="8.png" alt="Monitoring and Evaluation">
                    <div class="project-content">
                        <h3>Public and Third Sector - Monitoring and Evaluation</h3>
                        <p>Monitoring and evaluation of public policies and programs, with a focus on social impact and community engagement. Experience includes collaboration with D3S Consultoria and a tenure at the Secretaria Municipal de Direitos Humanos, contributing to the assessment and improvement of human rights initiatives.</p>
                        <p><strong>Confidential</strong></p>
                    </div>
                </div>

            </div>
        </div>
    </section>

</body>
</html>
