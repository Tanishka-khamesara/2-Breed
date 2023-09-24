# 2-Breed
hosted-link-> https://tanishka-khamesara.github.io/2-Breed/greed.html

![Screenshot (125)](https://github.com/Tanishka-khamesara/2-Breed/assets/127411985/c2b2a204-ddf0-4a35-a919-6a11466f230d)

used the screenshots of images given in the project as we are not provided with the images.somehow managed to set the images.
used display flex for adjusting the things.
Universal Selector and Global Styles:
css

* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
}
The * selector applies styles to all HTML elements on the page.
padding: 0; margin: 0; resets the default padding and margin for all elements to zero.
box-sizing: border-box; ensures that element sizing includes padding and borders.
font-family: Arial, Helvetica, sans-serif; sets the default font family for all elements to Arial or a similar sans-serif font.
Styling the Main Container:
css

.main {
    background: rgb(249, 247, 219);
    background: linear-gradient(
        0deg,
        rgba(249, 247, 219, 1) 0%,
        rgba(248, 247, 219, 1) 50%,
        rgba(233, 230, 195, 1) 100%
    );
}
.main selects an element with the class "main."
This code creates a linear gradient background with various shades of yellow and beige colors.
Styling the Main Container:
css

.container {
    height: 740px;
    width: 928px;
    margin: 0 auto;
    display: flex;
}
.container selects an element with the class "container."
Sets the height and width of the container and centers it horizontally using margin: 0 auto;.
Makes the container a flex container using display: flex;.
Styling the Logo:
css

.logo {
    background: url(./new\ side.png) no-repeat;
    width: 75px;
    height: 100vh;
}
.logo selects an element with the class "logo."
Sets a background image for the logo and ensures it doesn't repeat.
Fixes the width at 75 pixels and sets the height to 100% of the viewport height (100vh).
Styling Text within the Container:
css

.container span {
    font-size: 3rem;
    margin-left: 1rem;
}
Selects <span> elements within the container.
Sets the font size to 3 rem (relative to the root font size) and adds a left margin of 1 rem.
Styling Different Containers:
css

.container-tomato {
    background: #cd4007 url(./tomato.png) no-repeat;
    width: 216px;
    height: 96%;
}

.container-kiwi {
    background: #9fb31a url(./kiwi.png) no-repeat;
    width: 216px;
    height: 96%;
}
.container-tomato and .container-kiwi select elements with these specific classes.
Sets background colors and images for these containers, along with fixed widths and heights.
Styling the Top Section:
css

.top {
    height: 110px;
    width: 100%;
    position: relative;
    text-align: center;
}
Styles the top section of the page.
Sets a fixed height, full width, and centers text.
Styling Links in the Top Section:
css

.top a {
    text-decoration: none;
    color: #646464;
    font-size: 12px;
    font-weight: 700;
    padding-top: 56px;
}
Styles links within the top section.
Removes underlines (text-decoration: none;), sets text color, font size, font weight, and padding.
Styling Navigation Links:
css

.top a:hover {
    height: 110px;
}
When links in the top section are hovered over, they expand to a height of 110px.
Styling Main Page and About Us Links:
css

.main-page,
.about-us {
    position: absolute;
    right: 0;
    top: 0;
    width: 47px;
    height: 92px;
}

.main-page {
    background: url(https://priyanshu-240499.github.io/Assignments-CSS/2-breed/images/homeBg.gif) no-repeat;
}

.about-us {
    background: url(https://priyanshu-240499.github.io/Assignments-CSS/2-breed/images/about.gif) no-repeat;
}
markdown
- Styles links with classes `.main-page` and `.about-us`.
- Positions them absolutely at the top right corner.
- Sets background images for these links.
11. More Styling Rules:

The CSS code continues with styles for various elements, including text, buttons, images, forms, and footer sections. Each part of the code specifies how these elements should be displayed, including their size, color, background, and positioning.

![Screenshot (126)](https://github.com/Tanishka-khamesara/2-Breed/assets/127411985/e3ae7e19-c19d-4d8c-bb30-18a3c38b496f)

Styling the Features Section:
css

.features {
    height: 240px;
    background: rgb(233, 230, 195);
    background: linear-gradient(
        0deg,
        rgba(233, 230, 195, 1) 0%,
        rgba(232, 227, 193, 1) 95%,
        rgba(232, 227, 193, 1) 100%
    );
}
.features styles an element with the class "features."
Sets a fixed height of 240px and applies a linear gradient background from a light beige to a slightly darker beige.
Styling the Features Box Container:
css

.features-box {
    margin: 0 auto;
    width: 928px;
    display: flex;
}
.features-box styles a container for the features section.
Centers the container horizontally using margin: 0 auto;, sets its width to 928px, and makes it a flex container.
Styling the Features Description:
css

.features-desc {
    width: 473px;
    padding: 24px 31px 0 0;
    position: relative;
    margin-right: 31px;
}
.features-desc styles a section within the features box.
Sets a fixed width of 473px, adds padding to the top, right, and sets it as a relative position element. It also adds right margin.
Styling the Features Title:
css

.features-desc h2 {
    padding-left: 50px;
    font-size: 34px;
    color: #1d1d1d;
    line-height: 38px;
    font-weight: 400;
    background: url(./features.png) no-repeat;
}
Styles the title within the features description.
Adds padding to the left, sets font size, color, line height, font weight, and a background image.
Styling Features Description Text:
css

.features-desc p {
    margin-top: 9px;
    font-size: 12px;
    color: #575433;
    line-height: 19px;
}
Styles paragraphs within the features description.
Sets margin, font size, text color, and line height.
Styling Features Description Span:
css

.features-desc span {
    color: #8da00d;
    font-weight: 700;
}
Styles span elements within the features description.
Sets text color and font weight.
Styling a "Read More" Button with a Red Background:
css

.read-more-button.red {
    background-color: #cd4008;
}
Styles a button with the class "red" to have a red background color.
Styling a Login Form:
css

.login-form {
    height: 184px;
    width: 202px;
    margin: 19px 22px 0 0;
    border: #d7d3aa solid 1px;
    background: #f1eed0;
}
Styles a login form.
Sets its height, width, margin, border, and background color.
Styling Login Form Title:
css

.login-form h2 {
    width: 100%;
    height: 34px;
    padding-left: 33px;
    font-size: 18px;
    color: #212121;
    line-height: 30px;
    font-weight: 400;
    background: #ffffff url(./profile.png) no-repeat;
}
Styles the title within the login form.
Sets width, height, padding, font size, text color, line height, font weight, and a background image.
Styling the Login Form Box:
css

.login-form-box {
    display: flex;
    flex-direction: column;
    width: 168px;
    margin: 0 auto;
}
css

- Styles a container within the login form.
- Makes it a flex container with a column direction, sets a width, and centers it horizontally.
These are various styles for different elements and sections of a webpage, from features and login forms to buttons and footer sections. Each part of the code specifies how these elements should be presented on the web page.
