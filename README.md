# move-with-mouse

#### What is this?
This is a very basic representation of drag feature where a div block moves along with mouse.

#### Why?
This was created to crystalize JavaScript learning on:
* reposition a div using _clientX_ and _clientY_

#### Points to remember
* Note that the onmousemove event handler is assigned for the <body/> element, not for the \<div/>. This is because you must track the mouse movement over the entire page, not just within the \<div/>.
* The \<div/> that you want to move should have _**position**: absolute_
