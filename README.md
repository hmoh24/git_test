This is Hamsa's first git project.

This is a survey form that will aim to meet the criteria for the freecodecamp.org.
The criteria can be found at <https://www.freecodecamp.org/learn/responsive-web-design/responsive-web-design-projects/build-a-survey-form>
The topic of environmental survey is arbitrary and has been chosen to display the various forms of input required by the project user stories. There is no intention to deploy this project for use.

*Best Practices*

One criteria for the project is to have placeholder text in the inputs under the 'Details' section. This method of conveying information doesn't fall under the best practices for inputs and forms so has only been included to meet project criteria.

There is no supported way using HTML5 to set a checkbox input as required, and would need technology such as jQuery and javascript, which is out of the scope of this project.

A problem that arose during this project was the desire to place only one submit button for the entire page while there were save buttons next to all three details forms. It seems, at this stage, that it is not possible to have these two types of buttons coexist. The submit button for the entire page depends on a single form being wrapped around ALL inputs. The initial approach included forms wrapped around individual elements, such as radio buttons and checkboxes, despite these buttons not having a submit button of their own. This is important because it makes the use of the "required attribute". One submit button and form for all inputs means that someone cannot submit and leave the page without the required info, which would defeat the purpose of a survey. 