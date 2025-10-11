---
# Leave the homepage title empty to use the site title
title: ''
date: ''
type: landing

sections:

  - block: markdown
    id: pub-slider
    content:
      title: "Publications"
      text: |
        {{ partial "carousel-publications.html" . }}

  - block: resume-biography-3
    content:
      username: admin
      text: |
        Nuno holds a Ph.D. in Computer Science and Engineering. His current research interests include: software engineering, information systems (with special focus on decision support systems), data fusion, and software. He is member of the Instituto de Telecomunicações – IT in the Network Applications and Services group at UBI. He is the head of the Law Enforcement, Justice and Public Safety Research and Technology Transfer Laboratory (BSAFE Lab) at UBI. He is an IEEE Senior Member.

        He has around 100 scientific publications including book chapters, conference proceedings, and full-paper journals; e.g. IEEE Access, Applied Soft Computing, Computer Science Review, Artificial Intelligence in Medicine, Computer Methods and Programs in Biomedicine, Pervasive and Mobile Computing, and Measurement, just to mention a few. He has strong experience in R&D and cooperation at European level projects with both academia and industry.

      #button:
        #text: Download CV
        #url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded

  - block: markdown
    id: research
    content:
      title: 'My Research'
      text: |-
        Through active participation in international projects such as the Far-Future Strategy Development for STEM Higher Education Teachers ([FIT4FUTURE](https://www.befit4future.eu/)), HE Teachers and Institutions and Institutional Technology ([HIIT](https://www.hiitproject.eu/)) and various digital transformation initiatives like ([GRESINT](https://www.di.ubi.pt/~ngpombo/Gresint_PT.pdf/)), I have collaborated closely with leading researchers, prestigious universities, and companies. The publications stemming from these collaborations represent the culmination of intensive and fruitful teamwork. This international exposure has significantly shaped and enriched my research career.

        <div style="text-align: center; margin-top: 1rem;">
          <a href="https://www.scopus.com/authid/detail.uri?authorId=55389546100" target="_blank" style="background-color:#1a73e8;color:#fff;padding:0.6rem 1.2rem; border-radius:6px;text-decoration:none;display:inline-block;">Scopus</a>
          <a href="https://scholar.google.pt/citations?user=ZoDigNsAAAAJ&hl=pt-PT" target="_blank" style="background-color:#1a73e8;color:#fff;padding:0.6rem 1.2rem;margin-left:2rem;border-radius:6px;text-decoration:none;display:inline-block;">Google Scholar</a>
        </div>

    design:
      columns: '1'
      css_class: "wide-research"

  - block: markdown
    id: positions
    content:
      text: |
        <div class="max-w-prose" style="max-width: 1000px; margin: 0 auto; display: flex; flex-wrap: wrap; justify-content: space-between; box-sizing: border-box;">

          <!-- Coluna da esquerda -->
          <div style="flex: 0 0 48%; box-sizing: border-box;">
            <h3 style="text-align: center; margin-bottom: 3rem; font-weight: bold; ">Academic Positions</h3>
            <ul style="list-style: none; padding: 0; border-left: 2px solid #1a73e8; padding-left: 1rem;">
              <li style="margin-bottom: 0.8rem; padding: 0.3rem; transition: transform 0.2s, color 0.2s;">
                <strong>Associate Professor</strong><br>
                <span><em>Universidade da Beira Interior</em></span> <br>
                <span style="font-weight:bold; color:#1a73e8;">(2023 - presente) </span> 
              </li>
              <li style="margin-bottom: 1rem; padding: 0.3rem; transition: transform 0.2s, color 0.2s;">
                <strong>Assistant Professor</strong><br>
                <span><em>Universidade da Beira Interior</em></span><br>
                <span style="font-weight:bold; color:#1a73e8;">(2018 - 2023)</span> 
              </li>
              <li style="margin-bottom: 1rem; padding: 0.3rem; transition: transform 0.2s, color 0.2s;">
                <strong>Invited Assistant Professor</strong><br>
                <span><em>Universidade Lusófona</em></span><br>
                <span style="font-weight:bold; color:#1a73e8;">(2016 - 2018)</span> 
              </li>
              <li style="margin-bottom: 1rem; padding: 0.3rem; transition: transform 0.2s, color 0.2s;">
                <strong>Invited Assistant Professor</strong><br>
                <span><em>Universidade da Beira Interior</em></span><br>
                <span style="font-weight:bold; color:#1a73e8;">(2014 - 2018)</span> 
              </li>
              <li style="margin-bottom: 1rem; padding: 0.3rem; transition: transform 0.2s, color 0.2s;">
                <strong>Professor and Member of the Steering Committee</strong><br>
                <span><em>EU Master Care and Technology</em></span><br>
                <span style="font-weight:bold; color:#1a73e8;">(2016 - 2017)</span> 
              </li>
              <li style="margin-bottom: 1rem; padding: 0.3rem; transition: transform 0.2s, color 0.2s;">
                <strong>Monitor</strong><br>
                <span><em>Universidade da Beira Interior </em></span><br>
                <span style="font-weight:bold; color:#1a73e8;">(2008 - 2014)</span> 
              </li>
            </ul>
          </div>

          <!-- Coluna da direita -->
          <div style="flex: 0 0 48%; box-sizing: border-box;">
            <h3 style="text-align: center; margin-bottom: 3rem; font-weight: bold;">IT Positions</h3>
            <ul style="list-style: none; padding: 0; border-left: 2px solid #1a73e8; padding-left: 1rem;">
              <li style="margin-bottom: 1rem; padding: 0.3rem; transition: transform 0.2s, color 0.2s;">
                <strong>CTO and/or Mentor</strong><br>
                <span><em>in several national and international companies</em></span><br>
                <span style="font-weight:bold; color:#1a73e8;">(2010 - presente)</span>
              </li>
              <li style="margin-bottom: 1rem; padding: 0.3rem; transition: transform 0.2s, color 0.2s;">
                <strong>Project Leader</strong><br>
                <span><em>ASSEC - Sistemas de Informação e Multimédia</em></span><br>
                <span style="font-weight:bold; color:#1a73e8;">(2004 - 2010)</span>
              </li>
              <li style="margin-bottom: 1rem; padding: 0.3rem; transition: transform 0.2s, color 0.2s;">
                <strong>Team Leader</strong><br>
                <span><em>ASSEC - Sistemas de Informação e Multimédia</em></span><br>
                <span style="font-weight:bold; color:#1a73e8;">(2000 - 2004)</span>
              </li>
              <li style="margin-bottom: 1rem; padding: 0.3rem; transition: transform 0.2s, color 0.2s;">
                <strong>Programmer</strong><br>
                <span><em>Integer SGPS</em></span><br>
                <span style="font-weight:bold; color:#1a73e8;">(2000 - 2004)</span>
              </li>
            </ul>
          </div>
        </div>

    design:
      columns: '1'
      css_class: 'wide-positions'
      
  - block: resume-awards
    id: "awards"
    content:
      title: Honors and Awards
      username: admin
      text: ""
    design:
      columns: '2'
      css_class: "wide-resume-awards"
---
