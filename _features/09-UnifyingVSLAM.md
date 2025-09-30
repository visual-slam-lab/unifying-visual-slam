---
id: Unifying Visual SLAM
name: Unifying Visual SLAM
heading: Unifying Visual SLAM
div_class: lead
# subheading: Will Catch Your Eye
# image: "http://placehold.it/500x500"
---

A curated list of resources to help unify and standardize the landscape of Visual SLAM, Structure-from-Motion, datasets, tools, and educational content. This page collects links to key projects, foundational papers, tools, and talks.

🔗 Find the most up-to-date list here: [Unifying Visual SLAM GitHub Repository](https://github.com/VSLAM-LAB/Unifying-Visual-SLAM)

👋 Contributions are welcome! Feel free to open an issue or submit a pull request to suggest more tools, papers, or resources.

<style>
  .tab-buttons {
    display: flex;
    flex-wrap: wrap;
    border-bottom: 2px solid #ccc;
    margin-bottom: 1rem;
  }

  .tab-buttons button {
    background: none;
    border: none;
    border-bottom: 3px solid transparent;
    padding: 10px 16px;
    cursor: pointer;
    font-size: 2rem;
    transition: border-color 0.3s, background-color 0.3s;
  }

  .tab-buttons button:hover {
    background-color: #f0f0f0;
  }

  .tab-buttons button.active {
    border-bottom: 3px solid #007bff;
    font-weight: bold;
    color: #007bff;
  }

  .tab-content {
    display: none;
  }

  .tab-content.active {
    display: block;
  }

  table {
    width: 100%;
    border-collapse: collapse;
    margin-bottom: 1rem;
  }

  th, td {
    padding: 8px;
    border: 1px solid #ddd;
    text-align: left;
  }

  th {
    background-color: #f7f7f7;
  }
</style>

<div>
  <div class="tab-buttons">
    <button class="active" onclick="showTab('tab1', this)">VSLAM</button>
    <button onclick="showTab('tab8', this)">SfM</button>
    <button onclick="showTab('tab3', this)">Benchmark</button>
    <button onclick="showTab('tab4', this)">Datasets</button>
    <button onclick="showTab('tab2', this)">Education</button>
    <button onclick="showTab('tab5', this)">Foundational</button>
    <button onclick="showTab('tab6', this)">Talks</button>
    <button onclick="showTab('tab9', this)">Tools</button>
    <button onclick="showTab('tab7', this)">More</button>
  </div>

  <div id="tab1" class="tab-content active">
    <table>
      <thead><tr><th></th><th>State-of-the-art Visual SLAM</th></tr></thead>
      <tbody>
        <tr><td><a href="https://edexheim.github.io/mast3r-slam/">MASt3R-SLAM</a></td><td>MASt3R-SLAM: Real-Time Dense SLAM with 3D Reconstruction Priors</td></tr>
        <tr><td><a href="https://rmurai.co.uk/projects/GaussianSplattingSLAM/">MonoGS</a></td><td>Gaussian Splatting SLAM</td></tr>
        <tr><td><a href="https://github.com/princeton-vl/DPVO">DPVO</a></td><td>Deep Patch Visual Odometry/SLAM</td></tr>
        <tr><td><a href="https://github.com/princeton-vl/DROID-SLAM">DROID-SLAM</a></td><td>DROID-SLAM: Deep Visual SLAM for Monocular, Stereo, and RGB-D Cameras</td></tr>
        <tr><td><a href="https://github.com/raulmur/ORB_SLAM2">ORB-SLAM2</a></td><td>ORB-SLAM2: an Open-Source SLAM System for Monocular, Stereo and RGB-D Cameras</td></tr>
        <tr><td><a href="https://github.com/JakobEngel/dso">DSO</a></td><td>DSO: Direct Sparse Odometry</td></tr>
      </tbody>
    </table>
  </div>

  <div id="tab2" class="tab-content">
    <table>
      <thead><tr><th></th><th>Courses / Educational Materials / Tutorials</th></tr></thead>
      <tbody>
        <tr><td><a href="https://github.com/SLAM-Handbook-contributors/slam-handbook-public-release">SLAM Handbook</a></td><td>SLAM Handbook</td></tr>
        <tr><td><a href="https://www.youtube.com/watch?v=U6vr3iNrwRA&list=PLgnQpQtFTOGQrZ4O5QzbIHgl3b1JHimN_">SLAM-Course</a></td><td>SLAM-Course (2013/14; Cyrill Stachniss)</td></tr>
        <tr><td><a href="https://www.youtube.com/watch?v=BuRCJ2fegcc">SLAM - 5 Minutes with Cyrill</a></td><td>SLAM - 5 Minutes with Cyrill</td></tr>
      </tbody>
    </table>
  </div>

  <div id="tab3" class="tab-content">
    <table>
      <thead><tr><th></th><th>Software Frameworks/Libraries</th></tr></thead>
      <tbody>
        <tr><td><a href="https://github.com/alejandrofontan/VSLAM-LAB">VSLAM-LAB</a></td><td>VSLAM-LAB: A Comprehensive Framework for Visual SLAM Baselines and Datasets</td></tr>
        <tr><td><a href="https://github.com/gmberton/VPR-methods-evaluation">VPR-methods</a></td><td>VPR-methods-evaluation</td></tr>
        <tr><td><a href="https://github.com/luigifreda/pyslam">PySLAM</a></td><td>A python implementation of a Visual SLAM pipeline that supports monocular, stereo and RGBD cameras.</td></tr>
        <tr><td><a href="https://github.com/luigifreda/slamplay">slamplay</a></td><td>A collection of powerful tools to start playing and experimenting with SLAM in C++.</td></tr>
      </tbody>
    </table>
  </div>

  <div id="tab4" class="tab-content">
    <table>
      <thead><tr><th></th><th>Datasets</th></tr></thead>
      <tbody>
        <tr><td><a href="https://zuriich.github.io/CroCoDL/">CroCoDL</a></td><td>Augmented reality visual localization benchmark with data from legged robots, and evaluating human-robot, cross-device mapping and localization.</td></tr>
      </tbody>
    </table>
  </div>

  <div id="tab5" class="tab-content">
    <table>
      <thead><tr><th></th><th>Foundational Papers</th></tr></thead>
      <tbody>
        <tr><td><a href="https://www.robots.ox.ac.uk/~gk/publications/KleinMurray2007ISMAR.pdf">PTAM</a></td><td>Parallel Tracking and Mapping for Small AR Workspace</td></tr>
        <tr><td><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=4160954">MonoSLAM</a></td><td>MonoSLAM: Real-Time Single Camera SLAM</td></tr>
      </tbody>
    </table>
  </div>

  <div id="tab6" class="tab-content">
    <table>
      <thead><tr><th></th><th>Talks</th></tr></thead>
      <tbody>
        <tr><td><a href="https://www.youtube.com/watch?v=s9yc9-d-Vc8">Talk</a></td><td>Daniel Cremers | Deep and Direct Visual SLAM | Tartan SLAM Series</td></tr>
        <tr><td><a href="https://www.youtube.com/watch?v=PQFfJnmK26A">Talk</a></td><td>From SLAM to Spatial AI - Andrew Davison Robotics Today</td></tr>
        <tr><td><a href="https://www.youtube.com/watch?v=svzQgfkrxZc">Talk</a></td><td>Graph-based representations for Spatial-AI | Andrew Davison | Tartan SLAM Series</td></tr>
      </tbody>
    </table>
  </div>

  <div id="tab7" class="tab-content">
    <table>
      <thead><tr><th></th><th>Others</th></tr></thead>
      <tbody>
        <tr><td><a href="https://github.com/youngguncho/awesome-slam-datasets">Awesome SLAM Datasets</a></td><td>Collection of SLAM-related datasets</td></tr>
      </tbody>
    </table>
  </div>


  <div id="tab8" class="tab-content">
    <table>
      <thead><tr><th></th><th>Structure-from-Motion</th></tr></thead>
      <tbody>
        <tr><td><a href="https://github.com/colmap/glomap">GLOMAP</a></td><td>GLOMAP: Global Structure-from-Motion Revisited</td></tr>
        <tr><td><a href="https://github.com/colmap/colmap">COLMAP</a></td><td>COLMAP: General-purpose Structure-from-Motion (SfM) and Multi-View Stereo (MVS) pipeline with a graphical and command-line interface</td></tr>
      </tbody>
    </table>
  </div>
  
  <div id="tab9" class="tab-content">
    <table>
      <thead><tr><th></th><th>Other Tools</th></tr></thead>
      <tbody>
        <tr><td><a href="https://pixi.sh/latest/">Pixi</a></td><td>Pixi: A package management tool for developers</td></tr>
        <tr><td><a href="https://spectacularai.github.io/docs/sdk/core.html">Spectacular AI</a></td><td>Spectacular AI SDK: Platform-independent software solution for real-time 3D mapping and 6-DoF pose tracking</td></tr>
      </tbody>
    </table>
  </div>  
</div>

<script>
  function showTab(tabId, button) {
    document.querySelectorAll('.tab-content').forEach(el => el.classList.remove('active'));
    document.getElementById(tabId).classList.add('active');
    document.querySelectorAll('.tab-buttons button').forEach(btn => btn.classList.remove('active'));
    button.classList.add('active');
  }
</script>
