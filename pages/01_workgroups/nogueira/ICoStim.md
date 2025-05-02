title: ICoStim
---

<!--![ICoStim](https://www.vianna.de/01_workgroups/nogueira/icostim/ICoStim_AdobeStock_600111921.jpeg){style="float:right; margin-left:1em; width=50px"}-->

## Closed-loop fitting of cochlear implants by automated determination of stimulation parameters 
<br>

### Project description

The outcome of cochlear implant (CI) treatment relies on optimal parameter settings, which are currently determined through a labor-intensive, subjective fitting process. The ICoStim project aims to create a new system for objectively determining and optimizing these parameters using a closed-loop approach with a mobile electroencephalography (EEG) platform. This system records the patient's EEG response to CI stimulation, allowing for real-time adjustments and iterative optimization of the fitting. The approach does not require patient cooperation, making it suitable for patients that cannot give active feedback during the fitting process. The goal is a fast, accurate, and cost-effective fitting process that improves therapy outcomes.

<br>

Project coordinator: [eemagine Medical Imaging Solutions GmbH](https://www.eemagine.com/)

BMBF funding reference number: 13GW0721B

<img src="https://raw.githubusercontent.com/vianna-research/website/fb6f0bbdb6a585b4a5f58537047f7739cffa5f7f/pages/01_workgroups/nogueira/ICOSTIM/bmbf_logo.svg" alt="BMBF">

<br>

More information on <a href="https://www.tu-ilmenau.de/en/university/departments/department-of-computer-science-and-automation/profile/institutes-and-groups/institute-of-biomedical-engineering-and-informatics-bmti/research/measurement-and-stimulation-technologies-1/icostim-closed-loop-fitting-of-cochlear-implants-by-automated-determination-of-stimulation-parameters">TU Ilmenau</a> <i class="fa fa-external-link-square fa-lg"></i>

<!---
<div style="width: 200px; height: 20px; background-color: lightgray; border-radius: 5px; overflow: hidden;">
  <div style="width: 50%; height: 100%; background-color: green;"></div>
</div>
--->


<!-- Labels and Date Container with inline style -->
<div style="display: flex; justify-content: space-between; font-size: 14px; margin-bottom: 5px;">
  <div style="text-align: left;"><b>Start date</b></div>
  <div style="text-align: right;"><b>End date</b></div>
</div>

<!-- Date Container with inline style -->
<div style=" display: flex; justify-content: space-between; font-size: 14px; margin-bottom: 20px;">
  <div id="start-date"></div>
  <div id="end-date" style="text-align: right; "></div>
</div>

<!-- Progress Bar -->
<div style="width: 100%; height: 25px; background-color: lightgray; border-radius: 5px; overflow: hidden; position: relative;" id='outerBar'>
  <div id="progress" style="width: 0%; height: 100%; background-color: #00b0f0; transition: width 0.5s;"></div>
</div>

<script>
  // Define start and end dates
  const startDate = new Date("2025-03-01"); // Change to your actual start date
  const endDate = new Date("2027-02-29");   // Change to your actual end date
  const currentDate = new Date();

  // Format the dates as "1 December 2022"
  const options = { day: 'numeric', month: 'long', year: 'numeric' };
  const startFormatted = startDate.toLocaleDateString('en-GB', options);
  const endFormatted = endDate.toLocaleDateString('en-GB', options);

  // Set the formatted dates in the HTML
  document.getElementById("start-date").innerText = startFormatted;
  document.getElementById("end-date").innerText = endFormatted;

  // Calculate progress percentage
  const totalDuration = endDate - startDate;
  const elapsedTime = currentDate - startDate;
  let progressPercentage = (elapsedTime / totalDuration) * 100;

  // Ensure percentage is within bounds (0-100)
  progressPercentage = Math.max(0, Math.min(progressPercentage, 100));

  // Update progress bar width
  document.getElementById("progress").style.width = progressPercentage + "%";
</script>


<br>

### Other partners
<div style="display: flex; flex-wrap: wrap; gap: 10px;">
  <a href="https://www.eemagine.com/" style="text-decoration: none; border: none; display: inline-block; flex: 1 1 300px;"><img src="https://raw.githubusercontent.com/vianna-research/website/e019a02046e99bd68dec78e741a3da6101bc83ec/pages/01_workgroups/nogueira/ICOSTIM/eemagine_logo.svg" alt="eemagine Medical Imaging Solutions GmbH" style="width: 100%; height: auto; display: block;">
  </a>
  
  <a href="https://www.tu-ilmenau.de/en/" style="text-decoration: none; border: none; display: inline-block; flex: 1 1 300px;">
  <img src="https://raw.githubusercontent.com/vianna-research/website/e019a02046e99bd68dec78e741a3da6101bc83ec/pages/01_workgroups/nogueira/ICOSTIM/tu_ilmenau_logo.svg" style="width: 100%; height: auto; display: block;">    </a>
</div>






### Team
| Head of Research Group | &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; | &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |
| :----------------------------------- | :------------------------------------------------------------------------------------------------- | -------------------------------------: |
| ![Portrait](staff/Nogueiraklein.jpg) | [Dr.-Ing. Waldo Nogueira](https://vianna.de/01_workgroups/nogueira/staff/a_nogueira.html)          | <nogueiravazquez.waldo@mh-hannover.de> |

| Research Team &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; | &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; | &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |
| :----------------------------------- | :------------------------------------------------------------------------------------------------- | -------------------------------------: |
| ![Portrait](staff/Nina.jpg)	         | [Nina Aldag](https://vianna.uber.space/01_workgroups/nogueira/staff/nina.html)                     | <Aldag.Nina@mh-hannover.de>            |
| ![Portrait](staff/jonasSmall.jpg)	   | [Jonas Althoff](https://vianna.de/01_workgroups/nogueira/staff/jonas.html)	                        | <Althoff.Jonas@mh-hannover.de>         |



---

| Contact                 |                            |
| ------------------------|--------------------------- |
| Head of Research Group:<br>          | Prof. Dr.-Ing. Waldo Nogueira|
| Address: <br><br><br>   | DHZ-Deutsches HörZentrum Hannover<br> Karl-Wiechert-Allee 3 <br> 30625 Hannover <br> Deutschland |
| Phone:                  | +49 (0)511 532 8025 |
| Fax:                    | +49 (0)511 532 6833 |
| E-Mail:                 |<nogueiravazquez.waldo@mh-hannover.de>|


---



