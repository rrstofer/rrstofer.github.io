---
layout: default
title: Portfolio
---

<!-- =========================
     FEATURED PROJECTS
========================= -->

<section id="projects" class="section">

  <div class="section-heading">
    <span>01</span>
    <h2>Featured Projects</h2>
  </div>


  <!-- Workout Tracker -->

  <article class="featured-project">

    <div class="featured-project-image">
      <img
        src="{{ '/assets/img/Workout_Tracker.png' | relative_url }}"
        alt="Workout Tracker application">
    </div>

    <div class="featured-project-content">

      <p class="project-meta">
        MAY 2026 – PRESENT
      </p>

      <h3>Workout Tracker</h3>

      <p>
        I developed a full-stack workout tracking application designed to make
        recording workouts and monitoring strength progression simple and
        accessible across devices.
      </p>

      <p>
        The application was built as a Progressive Web App (PWA) using React
        and Vite, with Firebase Authentication and Cloud Firestore for
        authentication and persistent data storage. Users can log exercises,
        sets, repetitions, and weights while maintaining their own workout
        history.
      </p>

      <div class="tags">
        <span>JavaScript</span>
        <span>React</span>
        <span>Vite</span>
        <span>Firebase</span>
        <span>Firestore</span>
        <span>Vercel</span>
      </div>

      <div class="project-links">

        <a
          href="https://ryan-tuna-wt.vercel.app/"
          target="_blank"
          class="button primary">
          Open App
        </a>

        <a
          href="https://github.com/rrstofer/workout-tracker"
          target="_blank"
          class="button secondary">
          View Repository
        </a>

      </div>

    </div>

  </article>


  <!-- California Dashboard -->

  <article class="featured-project">

    <div class="featured-project-image">
      <img
        src="{{ '/assets/img/CA_Opioid_Dashboard.png' | relative_url }}"
        alt="California Opioid and MOUD Tableau Dashboard">
    </div>

    <div class="featured-project-content">

      <p class="project-meta">
        MAY 2025 – JUNE 2025
      </p>

      <h3>California Opioid & MOUD Prescribing Dashboard</h3>

      <p>
        I developed an interactive Tableau dashboard analyzing prescription
        trends for opioids and medications for opioid use disorder (MOUD)
        across California from 2010 to 2023.
      </p>

      <p>
        I worked with prescription and healthcare datasets that required data
        cleaning, transformation, validation, and integration before they
        could be used for visualization. The dashboard allows users to explore
        longitudinal prescribing trends and compare patterns across geographic,
        demographic, and prescription characteristics.
      </p>

      <div class="tags">
        <span>Tableau</span>
        <span>Python</span>
        <span>SQL</span>
        <span>Data Visualization</span>
        <span>Healthcare Analytics</span>
      </div>

      <div class="project-links">

        <a
          href="https://public.tableau.com/app/profile/ryan.stofer/viz/ISPOR2025Dashboard-ByPrescription/CURESDashboard"
          target="_blank"
          class="button primary">
          View Dashboard
        </a>

      </div>

    </div>

  </article>

</section>


<!-- =========================
     OTHER PROJECTS
========================= -->

<section class="section">

  <div class="section-heading">
    <span>02</span>
    <h2>Machine Learning & Research</h2>
  </div>


  <!-- GlucoGuard -->

  <article class="project-section">

    <div class="project-section-header">

      <div>
        <p class="project-meta">JANUARY 2024 – JUNE 2024</p>

        <h3>IMD Solutions Inc. – GlucoGuard</h3>
      </div>

    </div>

    <p>
      I collaborated with a team to develop a predictive model and an
      application for IMD Solutions Inc.'s newest product, GlucoGuard, aimed
      at individuals with type 1 diabetes. GlucoGuard continuously monitors
      glucose levels and administers glucose during nocturnal hypoglycemia
      to prevent low blood sugar events during sleep.
    </p>

    <p>
      I created a logistic regression model to forecast hypoglycemic events,
      particularly during sleep. In the absence of actual patient data, we
      utilized CGM data from Kaggle and achieved a precision of 93.1% across
      50 user data sets.
    </p>

    <div class="project-image-row">

      <img
        src="{{ '/assets/img/Prediction_Modeling.png' | relative_url }}"
        alt="GlucoGuard prediction model">

      <img
        src="{{ '/assets/img/Glucoguard_Wireframe.png' | relative_url }}"
        alt="GlucoGuard application wireframe">

    </div>

    <div class="tags">
      <span>Python</span>
      <span>Machine Learning</span>
      <span>Logistic Regression</span>
      <span>React Native</span>
    </div>

    <div class="project-links">

      <a
        href="https://github.com/rrstofer/rrstofer.github.io/blob/main/assets/img/MADO_Presentation_GlucoGuard.pptx"
        target="_blank"
        class="button secondary">
        View Poster
      </a>

    </div>

    <p class="confidential">
      Specifics and files are not shared for confidentiality purposes.
    </p>

  </article>


  <!-- LST -->

  <article class="project-section">

    <p class="project-meta">
      MAY 2022 – SEPTEMBER 2023
    </p>

    <h3>Super Resolution of Land Surface Temperature (LST) Images</h3>

    <p>
      I led a collaborative research project with a graduate student where we
      trained a U-Net-based convolutional neural network (CNN) to improve the
      resolution of coarse remote sensing data by utilizing high-resolution
      RGB imagery.
    </p>

    <p>
      We introduced a pre-training procedure using randomized transformations
      of RGB imagery to generate synthetic high-resolution data. Compared with
      a pixel-based statistical downscaling method, our deep learning approach
      achieved an improvement of approximately 28% in R².
    </p>

    <div class="project-image-single">

      <img
        src="{{ '/assets/img/Model_Figure.png' | relative_url }}"
        alt="LST super resolution model">

    </div>

    <div class="tags">
      <span>Python</span>
      <span>PyTorch</span>
      <span>TensorFlow</span>
      <span>Deep Learning</span>
      <span>Computer Vision</span>
    </div>

    <div class="project-links">

      <a
        href="https://github.com/ecohydro/lst-super-res"
        target="_blank"
        class="button secondary">
        View Repository
      </a>

      <a
        href="https://github.com/rrstofer/rrstofer.github.io/blob/main/assets/img/AGU_Poster.pdf"
        target="_blank"
        class="button secondary">
        View Poster
      </a>

    </div>

  </article>


  <!-- SLAC -->

  <article class="project-section">

    <p class="project-meta">
      JANUARY 2023 – JUNE 2023
    </p>

    <h3>UCSB Capstone – Deep Learning X-ray Diffraction Model</h3>

    <p>
      As part of the UCSB Capstone program, my group and I partnered with the
      Stanford Synchrotron Radiation Lightsource (SLAC SSRL) to research and
      develop deep learning models capable of classifying and predicting the
      resolution of individual X-ray diffraction shots.
    </p>

    <p>
      Using a ResNet-based architecture, our multi-lattice detection CNN
      achieved 94% accuracy, while the resolution quantification CNN attained
      a 0.96 Pearson correlation value on simulated data.
    </p>

    <div class="project-image-row">

      <img
        src="{{ '/assets/img/SLAC_1.png' | relative_url }}"
        alt="SLAC capstone model">

      <img
        src="{{ '/assets/img/SLAC_2.png' | relative_url }}"
        alt="SLAC capstone results">

    </div>

    <div class="tags">
      <span>Python</span>
      <span>PyTorch</span>
      <span>TensorFlow</span>
      <span>CUDA</span>
      <span>Deep Learning</span>
    </div>

    <div class="project-links">

      <a
        href="https://github.com/dermen/resonet"
        target="_blank"
        class="button secondary">
        View Repository
      </a>

      <a
        href="https://github.com/rrstofer/rrstofer.github.io/blob/main/assets/img/SLAC_Poster.pdf"
        target="_blank"
        class="button secondary">
        View Poster
      </a>

    </div>

  </article>

</section>


<!-- =========================
     DATA SCIENCE
========================= -->

<section class="section">

  <div class="section-heading">
    <span>03</span>
    <h2>Data Science & Visualization</h2>
  </div>


  <!-- Linguistic Isolation -->

  <article class="project-section">

    <p class="project-meta">
      APRIL 2024
    </p>

    <h3>2024 SoCal RUG Hackathon – Linguistic Isolation in California</h3>

    <p>
      I participated in a 36-hour hackathon where my team and I analyzed IPUMS
      US Census data to extract meaningful insights into linguistic isolation
      across the United States, with a particular focus on California.
    </p>

    <p>
      We performed geospatial analysis comparing 2014 and 2022 data across
      IPUMS regions and also explored a random forest model for predicting
      linguistic isolation.
    </p>

    <div class="project-image-row">

      <img
        src="{{ '/assets/img/State_Ling_Iso.png' | relative_url }}"
        alt="State linguistic isolation visualization">

      <img
        src="{{ '/assets/img/CA_Ling_Iso.png' | relative_url }}"
        alt="California linguistic isolation visualization">

    </div>

    <div class="tags">
      <span>R</span>
      <span>Data Visualization</span>
      <span>Geospatial Analysis</span>
      <span>Machine Learning</span>
    </div>

    <div class="project-links">

      <a
        href="https://github.com/rrstofer/rrstofer.github.io/blob/main/assets/img/RUG_Hackathon_04-2024.pdf"
        target="_blank"
        class="button secondary">
        View Summary
      </a>

    </div>

  </article>


  <!-- Hate Crime -->

  <article class="project-section">

    <p class="project-meta">
      JANUARY 2022 – MARCH 2022
    </p>

    <h3>National Hate Crime Model</h3>

    <p>
      During my undergraduate machine learning course, my partner and I
      developed a machine learning model capable of classifying offenders'
      races using hate crime records from the FBI Crime Data Explorer from
      2010 to 2019.
    </p>

    <p>
      We evaluated Random Forest, Naive-Bayes, Boosting, and Logistic
      Regression models. Our best-performing models were Random Forest and
      Boosting, both with an error rate of approximately 23%.
    </p>

    <div class="project-image-row">

      <img
        src="{{ '/assets/img/hate_crime_1.PNG' | relative_url }}"
        alt="Hate crime model analysis">

      <img
        src="{{ '/assets/img/hate_crime_2.PNG' | relative_url }}"
        alt="Hate crime model results">

    </div>

    <div class="tags">
      <span>R</span>
      <span>R Markdown</span>
      <span>Random Forest</span>
      <span>Naive-Bayes</span>
      <span>Boosting</span>
      <span>Logistic Regression</span>
    </div>

    <div class="project-links">

      <a
        href="https://github.com/rrstofer/rrstofer.github.io/blob/main/assets/img/hate_crime_project.html"
        target="_blank"
        class="button secondary">
        View Report
      </a>

      <a
        href="https://github.com/rrstofer/rrstofer.github.io/blob/main/assets/img/hate_crime_project.Rmd"
        target="_blank"
        class="button secondary">
        View R Markdown
      </a>

    </div>

  </article>

</section>


<!-- =========================
     SKILLS
========================= -->

<section id="skills" class="section">

  <div class="section-heading">
    <span>04</span>
    <h2>Skills</h2>
  </div>

  <div class="skills-grid">

    <div class="skill-group">

      <h3>Languages</h3>

      <div class="tags">
        <span>Python</span>
        <span>R</span>
        <span>SQL</span>
        <span>JavaScript</span>
        <span>C++</span>
      </div>

    </div>

    <div class="skill-group">

      <h3>Machine Learning</h3>

      <div class="tags">
        <span>PyTorch</span>
        <span>TensorFlow</span>
        <span>Machine Learning</span>
        <span>Deep Learning</span>
        <span>Computer Vision</span>
      </div>

    </div>

    <div class="skill-group">

      <h3>Development</h3>

      <div class="tags">
        <span>React</span>
        <span>Vite</span>
        <span>Firebase</span>
        <span>Firestore</span>
        <span>Git</span>
        <span>Vercel</span>
      </div>

    </div>

    <div class="skill-group">

      <h3>Analytics</h3>

      <div class="tags">
        <span>Tableau</span>
        <span>Data Visualization</span>
        <span>Statistical Modeling</span>
        <span>Data Analysis</span>
      </div>

    </div>

  </div>

</section>


<!-- =========================
     CONTACT
========================= -->

<section id="contact" class="section contact-section">

  <div class="section-heading">
    <span>05</span>
    <h2>Let's Connect</h2>
  </div>

  <p>
    I'm interested in opportunities involving data science, machine learning,
    AI, and software development.
  </p>

  <div class="hero-buttons">

    <a
      href="mailto:rrstofer@gmail.com"
      class="button primary">
      Email Me
    </a>

    <a
      href="https://github.com/rrstofer"
      target="_blank"
      class="button secondary">
      GitHub
    </a>

    <a
      href="https://www.linkedin.com/in/ryan-stofer/"
      target="_blank"
      class="button secondary">
      LinkedIn
    </a>

  </div>

</section>
