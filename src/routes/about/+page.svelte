<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About the UC Berkeley Nanotechnology Lab</title>
  <style>
    /* General Styling */
    body {
      font-family: 'Arial', sans-serif;
      background-color: #f4f4f4;
      margin: 0;
      padding: 0;
    }

    .page-content {
      font-family: 'Arial', sans-serif;
      padding: 2.5rem;
      background-color: #ffffff;
      color: #2c3e50;
      line-height: 1.8;
      width: 100%; /* Use full width */
      margin: 0; /* Remove centering margins */
      border-radius: 12px; /* Slightly rounded corners */
      box-shadow: 0 6px 15px rgba(0, 0, 0, 0.15); /* Subtle shadow for depth */
      position: relative; /* Ensure child elements like the image are positioned relative to this */
    }

    .section-title {
      font-size: 3rem;
      text-align: center;
      font-weight: bold;
      margin-bottom: 2rem;
      color: #003262; /* UC Berkeley Blue */
      border-bottom: 4px solid #FDB515; /* UC Berkeley Gold */
      display: inline-block;
      padding-bottom: 0.5rem;
    }

    .subsection-title {
      font-size: 2rem;
      margin-top: 2.5rem;
      margin-bottom: 1.5rem;
      font-weight: bold;
      color: #003262;
      position: relative;
    }

    .subsection-title::after {
      content: '';
      position: absolute;
      bottom: -5px;
      left: 0;
      width: 60px;
      height: 4px;
      background-color: #FDB515;
      border-radius: 2px;
    }

    .subsection-text {
      font-size: 1.3rem;
      margin-bottom: 2rem;
      color: #4a4a4a;
    }

    .information-list {
      list-style: none;
      padding: 0;
      margin: 2rem 0;
    }

    .information-list li {
      margin-bottom: 1.8rem;
      font-size: 1.2rem;
      background: #f9f9f9;
      border: 1px solid #e1e4e8;
      border-left: 5px solid #003262;
      padding: 1.5rem;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .information-list li:hover {
      transform: translateY(-6px);
      box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
    }

    .information-list li strong {
      font-weight: bold;
      color: #003262;
    }

    .cta-text {
      text-align: center;
      margin-top: 2.5rem;
      font-size: 1.3rem;
    }

    .cta-text a {
      color: #FDB515;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s ease;
    }

    .cta-text a:hover {
      color: #003262;
      text-decoration: underline;
    }

    .ucb-logo {
      position: absolute;
      top: 20px;
      right: 100px;;
      width: 170px;
      height: 170px;
    }

    /* Responsive Design */
    @media (max-width: 768px) {
      .page-content {
        padding: 1.5rem;
      }

      .section-title {
        font-size: 2.5rem;
      }

      .subsection-title {
        font-size: 1.8rem;
      }

      .subsection-text {
        font-size: 1.1rem;
      }

      .information-list li {
        font-size: 1rem;
        padding: 1rem;
      }

      .ucb-logo {
        width: 80px; /* Adjust size for smaller screens */
      }
    }
  </style>
</head>
<body>
  <div class="page-content">
    <!-- UCB Logo -->
    <img src="./ucb.png" alt="UC Berkeley Logo" class="ucb-logo">

    <h1 class="section-title">About the UC Berkeley Nanotechnology Lab</h1>

    <!-- Our Mission Section -->
    <h2 class="subsection-title">Our Mission</h2>
    <p class="subsection-text">
      At the UC Berkeley Nanotechnology Lab, we are pioneering the future by harnessing nanotechnology&apos;s transformative potential to address critical global challenges. Our mission is to drive innovative solutions that reshape healthcare, energy, environmental sustainability, and semiconductor technologies.
    </p>
    <p class="subsection-text">
      Through advanced sensor technologies and groundbreaking systems, we bridge the gap between scientific discovery and real-world application, aiming to revolutionize industries and enhance global quality of life.
    </p>

    <!-- Who We Are Section -->
    <h2 class="subsection-title">Who We Are</h2>
    <p class="subsection-text">
      Led by <strong>Dr. Waqas Khalid</strong>, an Associate Scientist at the California Institute for Quantitative Biosciences (QB3), our lab represents a cutting-edge collaborative ecosystem of innovation. Our interdisciplinary team comprises world-class experts in nanotechnology, materials science, electrical engineering, and emerging technological domains.
    </p>
    <p class="subsection-text">
      We are a dedicated collective of researchers, scientists, and engineers committed to pushing the boundaries of technological possibility. By cultivating a culture of collaborative excellence, we tackle the most pressing scientific and technological challenges of our era.
    </p>

    <!-- Our Teams Section -->
    <h2 class="subsection-title">Our Specialized Research Teams</h2>
    <p class="subsection-text">
      Our lab is strategically organized into specialized teams, each focusing on a distinct frontier of nanotechnology research and application. Together, these teams are pioneering breakthrough innovations:
    </p>
    <ul class="information-list">
      <li>
        <strong>Biosensor Technology Team</strong> - Developing cutting-edge biomolecule sensors to revolutionize healthcare diagnostics through advanced impedance spectroscopy technology.
      </li>
      <li>
        <strong>Analysis Team</strong> - Leveraging custom analysis frameworks and large language models to accelerate biomolecular research and generate transformative scientific insights.
      </li>
      <li>
        <strong>Drone Team</strong> - Reimagining aerial technology with ultracapacitor energy storage, establishing new benchmarks for efficient and sustainable drone operations.
      </li>
      <li>
        <strong>Microfluidics Team</strong> - Pioneering biological analysis through innovative carbon nanotube applications for precise fluid control in research and medical contexts.
      </li>
      <li>
        <strong>Energy Storage Team</strong> - Engineering sustainable, high-performance carbon-based ultracapacitors as revolutionary alternatives to conventional battery technologies.
      </li>
      <li>
        <strong>Exoskeleton Team</strong> - Creating neurally integrated wearable technologies that empower rehabilitation and restore human mobility through groundbreaking design.
      </li>
      <li>
        <strong>Lithography Team</strong> - Democratizing advanced manufacturing through carbon nanotube modulation, making sophisticated production techniques more accessible and scalable.
      </li>
      <li>
        <strong>Plasma Jet Team</strong> - Developing precision plasma stream technologies for transformative applications in energy production and industrial cutting processes.
      </li>
      <li> 
        <strong>Design Team</strong> - Crafting intuitive technological solutions that optimize functionality and bridge the critical gap between innovative concepts and practical implementation.
      </li>
    </ul>
    <p class="subsection-text">
      United by an unwavering passion for discovery, our teams collectively advance our vision of a technologically sophisticated and sustainable future.
    </p>
    <p class="cta-text">
      Explore the depth of our research and discover opportunities for collaboration by visiting <a href="/areas">our research areas</a>. Connect with our team leads who are eager to share insights and explore potential partnerships.
    </p>
  </div>
</body>
</html>
