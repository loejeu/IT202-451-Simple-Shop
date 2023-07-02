<table><tr><td> <em>Assignment: </em> IT202 Milestone1 Deliverable</td></tr>
<tr><td> <em>Student: </em> Joseph Leung (jl2334)</td></tr>
<tr><td> <em>Generated: </em> 7/1/2023 7:21:36 PM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IT202-451-M23/it202-milestone1-deliverable/grade/jl2334" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <ol><li>Checkout Milestone1 branch</li><li>Create a milestone1.md file in your Project folder</li><li>Git add/commit/push this empty file to Milestone1 (you'll need the link later)</li><li>Fill in the deliverable items<ol><li>For each feature, add a direct link (or links) to the expected file the implements the feature from Heroku Prod (I.e,&nbsp;<a href="https://mt85-prod.herokuapp.com/Project/register.php">https://mt85-prod.herokuapp.com/Project/register.php</a>)</li></ol></li><li>Ensure your images display correctly in the sample markdown at the bottom</li><ol><li>NOTE: You may want to try to capture as much checklist evidence in your screenshots as possible, you do not need individual screenshots and are recommended to combine things when possible. Also, some screenshots may be reused if applicable.</li></ol><li>Save the submission items</li><li>Copy/paste the markdown from the "Copy markdown to clipboard link" or via the download button</li><li>Paste the code into the milestone1.md file or overwrite the file</li><li>Git add/commit/push the md file to Milestone1</li><li>Double check the images load when viewing the markdown file (points will be lost for invalid/non-loading images)</li><li>Make a pull request from Milestone1 to dev and merge it (resolve any conflicts)<ol><li>Make sure everything looks ok on heroku dev</li></ol></li><li>Make a pull request from dev to prod (resolve any conflicts)<ol><li>Make sure everything looks ok on heroku prod</li></ol></li><li>Submit the direct link from github prod branch to the milestone1.md file (no other links will be accepted and will result in 0)</li></ol></td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> Feature: User will be able to register a new account </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add one or more screenshots of the application showing the form and validation errors per the feature requirements</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T20.14.49image.png.webp?alt=media&token=2f06ec3b-dd7c-4115-9869-32b70103aab2"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of invalid email<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T20.16.26image.png.webp?alt=media&token=ba9506f8-322f-4e0c-9c65-1a0811211d82"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of invalid password<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T20.16.56image.png.webp?alt=media&token=9bd6f6e1-5678-4ee3-98f5-f0bac36b3fbd"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of passwords not matching<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T20.17.44image.png.webp?alt=media&token=d6611055-afa2-4f26-bfe1-255168d43f8a"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of email not available<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T20.18.26image.png.webp?alt=media&token=a442bfb5-4228-4215-a723-2fab18adba3b"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of username not available<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T20.19.37image.png.webp?alt=media&token=cb10c819-768f-417b-8ce3-dfacde53800a"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of valid data filled in<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot of the Users table with data in it</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T20.20.45image.png.webp?alt=media&token=438240bf-9e17-48be-8a26-288dfe0ffe22"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of valid user data from Task 1<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add the related pull request(s) for this feature</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/loejeu/IT202-451/pull/15">https://github.com/loejeu/IT202-451/pull/15</a> </td></tr>
<tr><td> <em>Sub-Task 4: </em> Explain briefly how the process/code works</td></tr>
<tr><td> <em>Response:</em> <p>In a basic form, onsubmit triggers when the form submits and return a<br>the validate function. If it&#39;s true it&#39;s going to submit the form, if<br>false, it won&#39;t submit the form. The form is submitted as POST so<br>the data does not show in the URL. The password is handled by<br>checking for minimum length and if confirm password matches password. It is then<br>hashed and the valid information is stored into the database.&nbsp;<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 2: </em> Feature: User will be able to login to their account </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add one or more screenshots of the application showing the form and validation errors per the feature requirements</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T20.33.18image.png.webp?alt=media&token=bb3b162f-b3e9-4dc5-bdbd-8d40aa89c6ea"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of invalid password<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T20.34.19image.png.webp?alt=media&token=d8c1706d-289a-4678-adb6-ffea62ddc20b"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of non-existing user<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot of successful login</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T20.34.58image.png.webp?alt=media&token=11611cb9-ec21-4521-ba71-4be29df0894b"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of valid login and message that the user has logged in<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add the related pull request(s) for this feature</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/loejeu/IT202-451/pull/16">https://github.com/loejeu/IT202-451/pull/16</a> </td></tr>
<tr><td> <em>Sub-Task 4: </em> Explain briefly how the process/code works</td></tr>
<tr><td> <em>Response:</em> <p>The session data is dumped into the user session limiting the amount of<br>users we can support. The validation is checking if the email the user<br>typed is valid (having @ in it). user data from the database can<br>be pulled for future uses and readily available.<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> Feat: Users will be able to logout </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add a screenshot showing the successful logout message</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T20.47.52image.png.webp?alt=media&token=f824b4e9-1616-4635-8751-6f8d0c54c83d"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of message showing the user logged out<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot showing the logged out user can't access a login-protected page</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T20.48.42image.png.webp?alt=media&token=bcb79f57-919f-4d69-ae57-4abf4d46c653"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of message showing user must be logged in to access home.php<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add the related pull request(s) for this feature</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/loejeu/IT202-451/pull/17">https://github.com/loejeu/IT202-451/pull/17</a> </td></tr>
<tr><td> <em>Sub-Task 4: </em> Explain briefly how the process/code works</td></tr>
<tr><td> <em>Response:</em> <p>Session ID&#39;s are important in log in so other users cannot impersonate you.<br>A session cookie is created if you do not have have and destroyed<br>after logging out.&nbsp;<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 4: </em> Feature: Basic Security Rules Implemented / Basic Roles Implemented </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add a screenshot showing the logged out user can't access a login-protected page (may be the same as similar request)</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T21.32.24image.png.webp?alt=media&token=0603ec9b-764d-43cc-9950-97d346f67702"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of logged out user trying to access profile.php<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot showing a user without an appropriate role can't access the role-protected page</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T22.45.42image.png.webp?alt=media&token=187ab824-5457-4a41-af76-a3fd0fe757e4"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of user without admin role to access role-protected page<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add a screenshot of the Roles table with valid data</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T22.47.21image.png.webp?alt=media&token=ca3d56f1-6afc-4469-8021-8ec0e606e450"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of Roles table<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 4: </em> Add a screenshot of the UserRoles table with valid data</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T22.48.48image.png.webp?alt=media&token=224cc4f0-0c8d-4ae1-abb4-0e8f2debbe63"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of UserRoles table<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 5: </em> Add the related pull request(s) for these features</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/loejeu/IT202-451/pull/24">https://github.com/loejeu/IT202-451/pull/24</a> </td></tr>
<tr><td> <em>Sub-Task 6: </em> Explain briefly how the process/code works for login-protected pages</td></tr>
<tr><td> <em>Response:</em> <p>A session is created once a user is logged in to allow them<br>to visit the different pages on the site. If a user does not<br>have a session ID they cannot access these pages.<br></p><br></td></tr>
<tr><td> <em>Sub-Task 7: </em> Explain briefly how the process/code works for role-protected pages</td></tr>
<tr><td> <em>Response:</em> <p>If the user does not have the Admin role, they cannot have access<br>to the page.<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 5: </em> Feature: Site should have basic styles/theme applied; everything should be styled </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshots to show examples of your site's styles/theme</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T22.51.10image.png.webp?alt=media&token=0dfbc162-c40a-4164-869c-67e1020acb38"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of Home screen<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T22.51.30image.png.webp?alt=media&token=ad1bd84c-0ddf-4a06-9cba-2924a478e51b"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of Profile screen<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add the related pull request(s) for this feature</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/loejeu/IT202-451/pull/23">https://github.com/loejeu/IT202-451/pull/23</a> </td></tr>
<tr><td> <em>Sub-Task 3: </em> Briefly explain your CSS at a high level</td></tr>
<tr><td> <em>Response:</em> <p>Centered h1 tags and made the Login, Profile, and Logout colored blue. Also<br>made the input tags a solid border and changed background color.<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 6: </em> Feature: Any output messages/errors should be "user friendly" </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshots of some examples of errors/messages</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T22.56.36image.png.webp?alt=media&token=96a3a71d-f1d4-414b-9045-7fbf85dbc0c7"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of error displaying unavailable username<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T22.57.08image.png.webp?alt=media&token=a4547a45-7b71-4cea-97b7-f9ffdbdf976d"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of error displaying mismatched passwords<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T22.57.24image.png.webp?alt=media&token=b8012836-4540-48db-a01b-b9b7f575e1c4"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of error displaying unavailable email<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a related pull request</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/loejeu/IT202-451/pull/18">https://github.com/loejeu/IT202-451/pull/18</a> </td></tr>
<tr><td> <em>Sub-Task 3: </em> Briefly explain how you made messages user friendly</td></tr>
<tr><td> <em>Response:</em> <p>Instead of computer generated error messages, we replaced them with flash messages to<br>become human readable format.<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 7: </em> Feature: Users will be able to see their profile </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshots of the User Profile page</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T23.00.22image.png.webp?alt=media&token=ac8ab9e4-077e-49d9-935f-c168aedb2e37"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of profile page<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add the related pull request(s) for this feature</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/loejeu/IT202-451/pull/19">https://github.com/loejeu/IT202-451/pull/19</a> </td></tr>
<tr><td> <em>Sub-Task 3: </em> Explain briefly how the process/code works (view only)</td></tr>
<tr><td> <em>Response:</em> <p>Using safer_echo we can prefill the Email and Username data displayed in the<br>form on the Profile page.<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 8: </em> Feature: User will be able to edit their profile </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshots of the User Profile page validation messages and success messages</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T23.05.14image.png.webp?alt=media&token=46e06fdc-fff2-437a-9737-e589b46c1cd6"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of changed username/email<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T23.05.43image.png.webp?alt=media&token=051732c0-e972-45a7-986b-d3f581ce333d"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of changed password<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T23.06.01image.png.webp?alt=media&token=411dbac8-0277-43be-9b06-b853e430af42"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of mismatched passwords<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T23.06.29image.png.webp?alt=media&token=a0a8c164-947b-4af7-a77e-12e59416de01"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of unavailable username/email<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add before and after screenshots of the Users table when a user edits their profile</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T23.08.25image.png.webp?alt=media&token=b17727d1-4252-4a78-a736-632994b21508"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of user &#39;joeleung&#39; before the change<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T23.08.50image.png.webp?alt=media&token=191b5d20-423f-47b7-b7c1-d635b6b1dfde"/></td></tr>
<tr><td> <em>Caption:</em> <p>screenshot of user &#39;joeleung1&#39; after the change<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Add the related pull request(s) for this feature</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/loejeu/IT202-451/pull/19">https://github.com/loejeu/IT202-451/pull/19</a> </td></tr>
<tr><td> <em>Sub-Task 4: </em> Explain briefly how the process/code works (edit only)</td></tr>
<tr><td> <em>Response:</em> <p>The code checks if the email/user is valid before updating and checks for<br>duplicate email or user. If there is it displays an error message. Updating<br>a password is handled by checking is password and confirm password match and<br>have the required length.&nbsp;<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 9: </em> Issues and Project Board </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshots showing which issues are done/closed (project board) Incomplete Issues should not be closed</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fjl2334%2F2023-07-01T23.20.54image.png.webp?alt=media&token=e8eed5ac-ac6c-4c5c-bc1e-b9dce7ea6bbc"/></td></tr>
<tr><td> <em>Caption:</em> <p>No issues<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Include a direct link to your Project Board</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/users/loejeu/projects/4">https://github.com/users/loejeu/projects/4</a> </td></tr>
<tr><td> <em>Sub-Task 3: </em> Prod Application Link to Login Page</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://jl2334-prod.herokuapp.com/Project/login.php">https://jl2334-prod.herokuapp.com/Project/login.php</a> </td></tr>
</table></td></tr>
<table><tr><td><em>Grading Link: </em><a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IT202-451-M23/it202-milestone1-deliverable/grade/jl2334" target="_blank">Grading</a></td></tr></table>