<table><tr><td> <em>Assignment: </em> HW HTML5 Canvas Game</td></tr>
<tr><td> <em>Student: </em> Joseph Leung (jl2334)</td></tr>
<tr><td> <em>Generated: </em> 7/8/2023 8:12:10 PM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IT202-451-M23/hw-html5-canvas-game/grade/jl2334" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <ol><li>Create a branch for this assignment called&nbsp;<em>M6-HTML5-Canvas</em></li><li>Pick a base HTML5 game from&nbsp;<a href="https://bencentra.com/2017-07-11-basic-html5-canvas-games.html">https://bencentra.com/2017-07-11-basic-html5-canvas-games.html</a></li><li>Create a folder inside public_html called&nbsp;<em>M6</em></li><li>Create an html5.html file in your M6 folder (do not put it in Project even if you're doing arcade)</li><li>Copy one of the base games (from the above link)</li><li>Add/Commit the baseline of the game you'll mod for this assignment&nbsp;<em>(Do this before you start any mods/changes)</em></li><li>Make two significant changes<ol><li>Static changes like hard-coded colors/values will not count at all (i.e., changing shapes/colors/values that are globally defined and set only once.</li><li>Direct copies of my class example changes will not be accepted (i.e., just having an AI player for pong, rotating canvas, or multi-ball unless you make a significant tweak to it)</li><li>Significant changes are things that change with game logic or modify how the game works. Static changes like hard-coded colors/values will not count at all (i.e., changing shapes/colors/values that are globally defined and set only once). You may however change such values through game logic during runtime. (i.e., when points are scored, boundaries are hit, some action occurs, etc)</li></ol></li><li>Evidence/Screenshots<ol><li>As best as you can, gather evidence for your first significant change and fill in the deliverable items below.</li><li>As best as you can, gather evidence for your significant change and fill in the deliverable items below.</li><li>Remember to include your ucid/date as comments in any screenshots that have code</li><li>Ensure your screenshots load and are visible from the md file in step 9</li></ol></li><li>In the M6 folder create a new file called m6_submission.md</li><li>Save your below responses, generate the markdown, and paste the output to this file</li><li>Add/commit/push all related files as necessary</li><li>Merge your pull request once you're satisfied with the .md file and the canvas game mods</li><li>Create a new pull request from dev to prod and merge it</li><li>Locally checkout dev and pull the merged changes from step 12</li></ol><p>Each missed or failed to follow instruction is eligible for -0.25 from the final grade</p></td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> Game Info </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> What game did you pick to edit/modify?</td></tr>
<tr><td> <em>Response:</em> <p>Pong<br></p><br></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add the direct link to the html5.html file from Heroku Prod (i.e., https://mt85-prod.herokuapp.com/M6/html5.html)</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://jl2334-prod.herokuapp.com/M6/html5.html">https://jl2334-prod.herokuapp.com/M6/html5.html</a> </td></tr>
<tr><td> <em>Sub-Task 3: </em> Add the pull request link for this assignment from M6-HTML5-Canvas to dev</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/loejeu/IT202-451/pull/31">https://github.com/loejeu/IT202-451/pull/31</a> </td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 2: </em> Significant Change #1 </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Describe your change/modification</td></tr>
<tr><td> <em>Response:</em> <p>A significant change I added was introducing a second ball to the game.<br>It&#39;s direction is the same as the first ball and travels at a<br>constant speed.<br></p><br></td></tr>
<tr><td> <em>Sub-Task 2: </em> Screenshot of the change while playing (try your best as some changes may be nearly impossible to capture)</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-08T23.38.50image.png.webp?alt=media&token=ffabb61b-5940-44da-9d6d-95012818b7f1"/></td></tr>
<tr><td> <em>Caption:</em> <p>a screenshot of the AI opponent hitting the 2 balls back to the<br>player<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Screenshot of the relevant lines of code that implement your change (make sure your ucid and the date are shown in comments) In the caption briefly describe/explain how the code snippet works.</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-08T23.58.59image.png.webp?alt=media&token=145b18ad-9aed-4565-a172-167a7c83373a"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of init() function added drawables.push(ball2);<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-08T23.59.12image.png.webp?alt=media&token=899c8ef3-9c5e-4655-8aaa-918cf1092e86"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of reset position and speed of ball2<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-09T00.00.13image.png.webp?alt=media&token=485086e9-e382-4a14-b93f-f258ab09041a"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of moveball() function added ball2<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-09T00.00.25image.png.webp?alt=media&token=bce79d35-3c54-4d73-aef8-512f68e5150b"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of checkPaddleCollision logic for ball2<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> Significant Change #2 </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Describe your change/modification</td></tr>
<tr><td> <em>Response:</em> <p>Another significant change is modifying the scoreboard so that the game resets when<br>either ball is scored. Each ball counts towards the total score for the<br>player that scored. The right paddle also keeps track of the second ball<br>when playing.<br></p><br></td></tr>
<tr><td> <em>Sub-Task 2: </em> Screenshot of the change while playing (try your best as some changes may be nearly impossible to capture)</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-08T23.42.21image.png.webp?alt=media&token=5d2d61c5-6cf5-4dea-8e7d-88a0224d8098"/></td></tr>
<tr><td> <em>Caption:</em> <p>a screenshot of the score count going up from either ball passing a<br>paddle<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Screenshot of the relevant lines of code that implement your change (make sure your ucid and the date are shown in comments) In the caption briefly describe/explain how the code snippet works.</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-09T00.04.59image.png.webp?alt=media&token=e430d3dc-dca7-406c-98f8-137d60db3a3f"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of doAI() function but I pass ball into it<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-09T00.05.50image.png.webp?alt=media&token=812f721d-17af-4f45-94a4-e9e71031020b"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of checkScore() function and added logic to count score of ball2<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-09T00.06.26image.png.webp?alt=media&token=cf2e3502-66a1-4dab-9835-b13e102bbe26"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of gameLoop() function with added doAI(ball) and doAI(ball2)<br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 4: </em> Discuss </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Talk about what you learned during this assignment and the related HTML5 Canvas readings (at least a few sentences for full credit)</td></tr>
<tr><td> <em>Response:</em> <p>I learned how to create game objects such as paddles and balls, handle<br>user input, implement basic game logic for movement and collision detection, and keep<br>track of scores.&nbsp;The code showcases techniques for animating the game using a game<br>loop and rendering graphics on a canvas element. This assignment also provided me<br>insight into building interactive games and understanding core concepts of game development.<br><br></p><br></td></tr>
</table></td></tr>
<table><tr><td><em>Grading Link: </em><a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IT202-451-M23/hw-html5-canvas-game/grade/jl2334" target="_blank">Grading</a></td></tr></table>