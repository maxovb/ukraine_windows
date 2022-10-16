# Windows for Ukraine

Sharespace for emergency solutions to replace windows blown out by the war in Ukraine

## Submission
Solution should be submitted as a pdf file (max 10mb) with a written set of instructions and pictures. We will request Youtube videos from the most successfull solutions once the beta-testers have evaluated them.

If possible, use Git to submit your solution, see the detailed instructions at the bottom of this page. If this is not possible, use this google form: https://forms.gle/hxd8z6jKdvMSpaW29.


## Solutions table

| Solution name                                    | Materials required                | Contributors                                      |
|:------------------------------------------------:| :-------------------------------- | ------------------------------------------------- |
| Double glazing with plastic-wrapped wooden frame | Wood, plastic film, strings, wool | Harry Blakiston Houson, Max-Olivier Van Bastelaer |

## Situation
Since the start of the war, an estimated 1-10 million windows have been blown out in Ukraine. Soaring energy prices and cold winter temperatures make this an urgent problem as windows are a key component of good building insulation. Most people have come up with emergency solutions to block air from passing through with materials such as plywood or plastic wrap. However, many of those solutions will not last through the whole winter as they are not insulating enough. We believe that - all together - we can come up with a solution that Ukrainians can use to replace the shattered windows and go through the harsh winter months.

## Problem to solve
Design a method to replace the shattered windows in Ukraine. The solution should most importantly be well insulating, but other key factors are listed in the requirements section. Ideally the product should only require materials which can be easily found by the locals in Ukraine, so everyday material and common DIY equipment. Solutions requiring materials to be shipped to Ukraine will also be considered but should be avoided. 

Examples of current solutions can be seen here (add link to Harry's pdf).

You are more than welcome to fork on any of the current solutions if you think you have specific improvments on their designs.

If you would like more information on the problem and thoughts on your proposed solution reach out to us with some suggested times (30 min slots): hcbh96 (at) gmail.com 

## Requirements

- Insulating (as good as or close to double glazing insulation)
- Safe if a bomb detonates
- Only requiring materials easily available for Ukrainians (everyday materials)
- Simple to produce and install
  - No professional skills or extreme physical strength required 
  - Little/no machinery required
- Cheap
- Water (rain, hail, snow, fog) resistant
- Transparent (translucent at least)
- Durable to last 6 months

## Timeline 
**Solutions are urgently needed**, you are invited to submit your solution on the website as soon as possible. We will welcome solutions during the whole winter to let you iterate on the feedback received from the local users. Do not hesitate to send your first solution and send better optimised solutions later on after receiving more feedback.

## Benefits
Teams and creators of each solution will be named alongside the solutions they provide. We will look as much as possible to highlight the team and individuals who worked on the solution.

## How to use git

## Instructions to submit with Git

If you have never used git, go the previous section "How to use git". Then follow these instructions. 

All terminal commands listed below should be run in the same folder (where you want to download this project).
1. In terminal, run:
   ```
   git clone https://github.com/maxovb/ukraine_windows.git
   ``` 
2. Create a new branch. Replace `<name_of_your_solution>` in the code below by the name of your solution and replacing spaces ` ` with underscores `_`. In terminal run:
   ```
   git checkout -b <name_of_your_solution>
   ```
3. Upload this new branch to github. In terminal run:
   ```
   git push –set-upstream origin <name_of_your_solution>
   ```
4. In the `ukraine_windows` folder, create a new folder `<name_of_your_solution>`. Add your pdf files and any other additional files in this folder.
5. In terminal run:
   1. ```git add <name_of_your_solution>```
   2. ```git commit -m "<name_of_the_solution>,<list_of_contributors>"```
   3. ```git push```
6. Create a pull-request for this new branch:
   1. On this webpage, click on "Pull requests"
   2. Click on "New pull request"
   3. Leave the first box as ```base:main``` and change the second one to ```<name_of_your_solution```.
   4. Click on "Create pull request"
   5. Add any comments you would like to add and click "Create pull request" once again.
All done ! Thank you for submitting your solution through git!






