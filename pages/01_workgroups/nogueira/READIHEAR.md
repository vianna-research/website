title: READIHEAR
---

![READIHEAR](https://www.vianna.de/01_workgroups/nogueira/readihear/readihear.png){style="float:right; margin-left:1em"}

## Rehabilitation and Diagnosis of Hearing Loss based on Electric Acoustic Interaction. 
<br/>

### Project description

Hearing loss is the most common sensory deficit in the elderly. As a chronic health problem, hearing loss can have severe impacts on a person’s mental health and social participation. One widely used solution is cochlear implants, hearing prosthetics that stimulate the auditory nerve with electrodes placed inside the cochlea. The EU-funded READIHEAR project will investigate the fundamental interaction mechanisms between electric and acoustic stimulation across the auditory pathway, from the cochlea to the auditory cortex. READIHEAR aims to set the basis for a new generation of diagnostic and treatment devices for hearing loss.

More information: [EU Project Website](https://cordis.europa.eu/project/id/101044753)

Grant agreement ID: 101044753

<!---
<div style="width: 200px; height: 20px; background-color: lightgray; border-radius: 5px; overflow: hidden;">
  <div style="width: 50%; height: 100%; background-color: green;"></div>
</div>
--->

<div style='width:300px;'>
<!-- Labels and Date Container with inline style -->
<div style="display: flex; justify-content: space-between; font-size: 14px; margin-bottom: 5px;">
  <div style="text-align: left;">Start date</div>
  <div style="text-align: right;">End date</div>
</div>

<!-- Date Container with inline style -->
<div style="width: 300px; display: flex; justify-content: space-between; font-size: 14px; margin-bottom: 20px;">
  <div id="start-date"></div>
  <div id="end-date" style="text-align: right; "></div>
</div>

<!-- Progress Bar -->
<div style="width: 300px; height: 25px; background-color: lightgray; border-radius: 5px; overflow: hidden; position: relative;">
  <div id="progress" style="width: 0%; height: 100%; background-color: #00b0f0; transition: width 0.5s;"></div>
</div>
</div>

<script>
  // Define start and end dates
  const startDate = new Date("2022-12-01"); // Change to your actual start date
  const endDate = new Date("2027-11-30");   // Change to your actual end date
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

### Objective
Hearing loss is the most common sensory deficit in the elderly, and it is becoming a severe social as well as a health problem. Across the whole lifespan, from new-borns to the elderly, hearing loss impairs the exchange of information, thus significantly impacting everyday life, causing loneliness, isolation, dependence, frustration and communication disorders. Cochlear implants (CIs) are hearing prosthetics that stimulate the auditory nerve with electrodes placed inside the cochlea. CIs are gradually being implanted in subjects retaining low-frequency residual hearing. In general, these subjects obtain large benefits in speech perception from electric acoustic stimulation, although large variability exists and some subjects do not benefit. Therefore, it is highly desirable to create objective diagnostics to assess acoustic low-frequency hearing to indicate cochlear implantation, to monitor and preserve hearing during the implantation procedure and to understand the mechanisms related to electric acoustic stimulation benefits.
The ground-breaking nature of the READIHEAR project is to investigate the fundamental interaction mechanisms between electric and acoustic stimulation across the auditory pathway, from the cochlea up to the auditory cortex. The fundamental understanding will set the basis for a new generation of diagnostic devices of hearing loss that combine for the first time minimally invasive electric acoustic stimulation. Moreover, READIHEAR will assay a novel auditory prosthetic that makes use of the interaction mechanisms between acoustic and electric stimulation delivered through minimally invasive electrodes. These developments will be beneficial for a large population suffering from hearing loss across the whole lifespan, from young children who will benefit from improved hearing diagnostics to the elderly population who will benefit from minimally invasive electric acoustic stimulation technology as the treatment for age-related hearing loss.

### Team
| Head of Research Group | &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; | &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |
| :----------------------------------- | :------------------------------------------------------------------------------------------------- | -------------------------------------: |
| ![Portrait](staff/Nogueiraklein.jpg) | [Dr.-Ing. Waldo Nogueira](https://vianna.de/01_workgroups/nogueira/staff/a_nogueira.html)          | <nogueiravazquez.waldo@mh-hannover.de> |

| Research Team &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; | &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; | &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; |
| :----------------------------------- | :------------------------------------------------------------------------------------------------- | -------------------------------------: |
| ![Portrait](staff/Krueger6.jpg)      | [Dr.-Ing. Benjamin Krüger](https://www.vianna.de/01_workgroups/nogueira/staff/benjamin.html)       | <Krueger.Benjamin@mh-hannover.de>      |
| ![Portrait](staff/Alrutz.jpg)	       | [Dr. rer. nat. Daniel Kipping](https://vianna.uber.space/01_workgroups/nogueira/staff/daniel.html) | <Kipping.Daniel@mh-hannover.de>	       |
| ![Portrait](staff/franklin.jpg)	     | [Franklin Alvarez ](https://vianna.de/01_workgroups/nogueira/staff/franklin.html)                  | <Alvarez.Franklin@mh-hannover.de>	     |
| ![Portrait](staff/Hanna.jpeg)	       | [Hanna Dolhopiatenko](https://vianna.uber.space/01_workgroups/nogueira/staff/hanna.html)           | <Dolhopiatenko.Hanna@mh-hannover.de>   |
| ![Portrait](staff/Nina.jpg)	         | [Nina Aldag](https://vianna.uber.space/01_workgroups/nogueira/staff/nina.html)                     | <Aldag.Nina@mh-hannover.de>            |
| ![Portrait](staff/patrickSmall.jpg)	 | [Patrick Hinz](https://vianna.de/01_workgroups/nogueira/staff/patrick.html)	                      | <Hinz.Patrick@mh-hannover.de>          |
| ![Portrait](staff/zhang.jpg)      	 | [Yixuan Zhang](https://vianna.de/01_workgroups/nogueira/staff/zhang.html)	                        | <Zhang.Yixuan@mh-hannover.de>          |
| ![Portrait](staff/empty.jpg)	       | [Robert Hart](https://vianna.de/01_workgroups/nogueira/staff/hart.html)	                          | <Hart.Robert@mh-hannover.de>           |


### Publications


### Conferences

---

| Contact                 |                            |
| ------------------------|--------------------------- |
| Head of Research Group:<br>          | Prof. Dr.-Ing. Waldo Nogueira|
| Address: <br><br><br>   | DHZ-Deutsches HörZentrum Hannover<br> Karl-Wiechert-Allee 3 <br> 30625 Hannover <br> Deutschland |
| Phone:                  | +49 (0)511 532 8025 |
| Fax:                    | +49 (0)511 532 6833 |
| E-Mail:                 |<nogueiravazquez.waldo@mh-hannover.de>|


---


