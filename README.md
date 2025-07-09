# sign-up-form

The sign-up form project is about the implementation of the sign-up form for an imaginary service. Given the design of the website, create the website from scratch and implement the sign-up form for users to enter their personal information, contact information, and create the password for their account. The project allows for practice with the implementation of forms and form validation in preparation for server-side validation. The project also allows for practice with more advanced CSS properties compared to the CSS properties learned in the Foundaions course.

## Image Sidebar

The design of the image sidebar required absolute and relative positioning to position the logo of the imaginary service and the caption of the image on top of the background image. The use of absolute positioning removed the logo of the imaginary service and the caption of the image from the document flow and the use of relative positioning allowed them to be absolutely positioned relative to the container for the image sidebar.

The design of the logo for the imaginary service also required absolute and relative positioning because the width of the image for the logo prevented the text for the name of the imaginary service to be placed next to the image for the logo. The use of absolute positioning removed the text for the name of the imaginary service from the document flow and the use of relative positioning allowed for the text to be placed relative to the container for the logo of the imaginary service alongside the image for the logo.

The consequence of the use of absolute positioning to position the caption of the image at the bottom of the background image was that the caption could not be centered with flexbox because the caption was removed from the document flow. To center the caption at the bottom of the background image, the ```top``` property was used to push the caption so that the left corner of the caption is located at the center of the image sidebar. The ```translate``` function was used to perform a horizontal translation to the left by half the length of the caption to move the center of the caption to the center of the image sidebar.

