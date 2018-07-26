---
layout: page
title: About
permalink: /about/
---

A Software Engineer by trade, a problem solver by nature. Learning new skills and finding solutions to hard problems is what drives me. 

I have 10+ years of experience in a diverse set of technology stacks in fields ranging from Information Security and Cryptography Applications to Medical Devices and Telecom Sales. 

Currently aspiring to make an impact in the Blockchain / Cryptocurrency space.

### Some work that I'm proud of

<button class="toggle-irony">Toggle Ironic Frustrations mode!</button>

- Secured a secret industrial automation process worth millions of dollars by designing and implementing an API to wrap it and embed it into a Secure Enclave. The solution included a C++ REST API, a LabVIEW client and a React/RxJS app for admin/config.

<div class="irony hidden">
Impressive stuff indeed! Now the corporate spies will have to resort back to the classic tactic of threatening the <strong>one engineer</strong> in that multinational that has all the secret source code in his day to day laptop.

<img src="https://imgs.xkcd.com/comics/security.png" style="margin: 1em auto 0; display: block;">
</div>

- Published a [peer-reviewed paper](https://link.springer.com/chapter/10.1007/978-3-642-53997-8_10) in an international conference. 

<div class="irony hidden">
Don't bother to read it! No impressive breakthroughs there. What I'm proud off is that I was stubborn enough to finish that paper. This enabled me to complete my Master's Degree and since I had to present it at the conference, might as well enjoy the trip. Visiting Germany, Austria, The Netherlands, England and Scotland was a great experience!
</div>

- Got my name as one of the creators in a patent by leading the development of the Java reference implementation of the Brazilian Digital Signature Standard. Patent (br 13474-3).

<div class="irony hidden">
Vanity metrics detected! By the way that standard is rubbish. I wrote a lengthy report explaining them why, but we all know what governments do when their programs don't work: They expand them!
</div>

- Saved the heartbeats of hundreds of beloved pets. Did this by successfully creating and deploying a custom database migration tool for the embedded database of the EKG desktop app relied upon by dozens of veterinarians and cardiologists in the field. The previous database structure didn't employ any sorts of constraints, foreign keys or normalization. The tool, written in Java and SQL, had to extract all data carefully considering the correct dependency order and then populate the new database.

<div class="irony hidden">
The best part is this: None of the customers ever appreciated the hard work that went into it! Just kidding, that was the whole point. This one was actually awesome!
</div>

### Contact me

[felipewer@gmail.com](mailto:felipewer@gmail.com)

<script>
  document.querySelector('.toggle-irony').addEventListener('click', function() {
    document.querySelectorAll('.irony').forEach(function(comment) {
      comment.classList.toggle('hidden');
    })
  })
</script>
