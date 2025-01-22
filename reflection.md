I had some trouble getting my images to show correctly as I wished at the end of the project2 portfolio check in. This time around I got to fixing that to make sure things would run smoothly. Then I added style and separated the css and html files. This called for cleaner and more organized coding. I had trouble getting the navbar to properly work on both computer and phone.This called for the need of a javaScript at end of html file. This in addition to much trial and error with the css styling.The section below is what toggled the menu for phone screens while leaving the menu as is on larger ipad and computer screens.

@media (max-width: 768px) {
    .navbar ul {
        display: none; /* Hide by default for mobile */
        flex-direction: column;
        position: absolute;
        top: 60px;
        right: 20px;
        background-color: #004d00;
        border-radius: 5px;
        box-shadow: 0 2px 5px rgba(0, 0, 0, 0.5);
        padding: 10px;
    }

    .navbar ul.active {
        display: flex;
    }

    .hamburger {
        display: flex; /* Show hamburger for mobile */
    }
}