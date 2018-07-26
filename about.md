---
layout: page
title: About
permalink: /about/
---

A Software Engineer by trade, a problem solver by nature. Learning new skills and finding solutions to hard problems is what drives me. 

I have 10+ years of experience in a diverse set of technology stacks in fields ranging from Information Security and Cryptography Applications to Medical Devices and Telecom Sales. 

Currently aspiring to make an impact in the Blockchain / Cryptocurrency space.

### Work that I'm proud of

- Secured a secret industrial automation process worth millions of dollars by designing and implementing an API to wrap it and embed it into a Secure Enclave. The solution included a C++ REST API, a LabVIEW client and a React/RxJS app for admin/config.

<div class="irony hidden">
  Impressive stuff indeed! Now the corporate spies will have to resort back to the classic tactic of threatening the <strong>one engineer</strong> in that multinational that has all the secret source code in his day to day laptop.
  <img class="meme" src="https://imgs.xkcd.com/comics/security.png">
</div>

- Published a [peer-reviewed paper](https://link.springer.com/chapter/10.1007/978-3-642-53997-8_10) in an international conference. 

<div class="irony hidden">
  <img class="meme" width="448" src="https://i.kym-cdn.com/photos/images/newsfeed/000/200/420/BRTky.jpg">
  I would not go so far as to consider myself a scientist tough. After all, it was a requirement to complete my Master's Degree :P. Either way, I got to travel and that trip was awesome. \o/
</div>

- Got my name listed as one of the creators in a patent by leading the development of the Java reference implementation of the Brazilian Digital Signature Standard. Patent (br 13474-3).

<div class="irony hidden">
  Vanity metrics detected! Although we did our best on the implementation side, I saw lots of problems with the standard specification. I even wrote a lengthy report explaining them why, but we all know what governments do when their programs don't work: They double down and expand it!
</div>

- Saved the heartbeats of hundreds of beloved pets. Achieved this by successfully creating and deploying a custom database migration tool for the embedded database of the EKG desktop app relied upon by dozens of veterinarians and cardiologists in the field. The previous database structure didn't employ any sorts of constraints, foreign keys or normalization. The tool, written in Java and SQL, had to extract all data carefully considering the correct dependency order and then populate the new database.

<div class="irony hidden">
  Irony: Because it worked flawlessly, none of the customers ever knew what was going on, nor appreciated the hard work that went into it! But those are the rules of the game we play, right!
</div>

### Contact me

[felipewer@gmail.com](mailto:felipewer@gmail.com)

<script>
  console.log('Press (Alt + I) to display some ironic enhancements.');
  document.addEventListener ('keydown', function (event) {
    if (event.altKey && event.code === 'KeyI') {
      document.querySelectorAll('.irony').forEach(function(comment) {
        comment.classList.toggle('hidden');
      })
      window.location = '#Work that I\'m proud of';
    }
  });
</script>
