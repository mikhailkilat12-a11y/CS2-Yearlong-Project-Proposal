# CS2-Yearlong-Project-Proposal
Project Title: Online Confirmation App For Interns of PSHS-EVC

Problem Statement: Sometimes, the dorm manager is not available. That is why we made an app to fill out the leave pass online. The parent/s of the intern sometimes take a long time to send the verification to the dorm faculty.

Project Objectives:
-The app aims to allow PSHS-EVC interns to easily fill out the leave pass without consuming too much time.
-The app will quickly deliver the confirmation of the parent/s of the intern

Planned Features:
-Respective passwords for interns and dorm managers
-Choices of reasons to leave the campus
-Confirmation of the intern’s parent/s

Planned Inputs and Outputs:
Inputs:
-Option whether you are an intern or a dorm manager
-Respective password depending on the previous input
-Grade level and section of the intern
-Phone numbers and email addresses of the intern’s parent/s
-Reason to leave the campus
-Option whether the parent/s allowed the intern to leave or not

Outputs:
-Reason to leave the campus given by the intern
-Question to the parent/s to allow their child to leave or not
-Notification to the intern if their parent/s approved or not

Logic Plan:
START

Print “Are you an intern or a dorm manager?”

Enter option

Print “Enter your full name:”

Enter name

Print “Enter the respective password (EVC_INTERN/EVC_DORM_MANAGER):“

Enter password

Print “Enter your grade level and section:“

Enter level, section

Print “What is your reason to leave the campus? (Go home, school competition, others)

Enter reason

[IF reason = others

Print “Enter your specific reason to leave:”

Enter specific_reason

Print “Your child is requesting to go off-campus. Their reason is:” &specific_reason& “Do you want to let them go? (type y/n or Y/N)”

Enter confirm]

[ELSE

Print “Your child is requesting to go off-campus. Their reason is:” &reason& “Do you want to let them go? (type y/n or Y/N)”

Enter confirm

IF confirm = n/N

Print “Your parent did not agree”

ELSE

Print “The request is approved.”]
