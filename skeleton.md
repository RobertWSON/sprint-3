What happens to the layout when you resize the screen to less than 550px and how do you think that works?

As the screen resolution reduces below 550px a media query kicks in and increases the container size from 80% to 85% of the screen size. When you are on a device that has below 550px sceen resolution the container size of 85%, contains content inside it that takes up all of its 85%, because the padding is 0. This means that if there are more than one column in the container above 550px, on a device below 550px it collapses and reduces to one column.   







