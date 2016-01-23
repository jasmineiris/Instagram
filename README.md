Instagram Feed

# Lab 1 - *Instagram App*

**Instagram Feed** This exercise is to practice using table views by building a simple Instagram app.

Time spent: **2** hours spent in total

## User Stories

## Milestone 1: Setup 
1. Create a new project using the Single View Application template
2. Setup CocoaPods (a dependency manager for iOS projects)
3. Disable Auto Layout for the Main.storyboard (Auto Layout is a more advanced topic that will be introduced later in the course)
4. Turn off App Transport Security
5. Send a test request to Instagram
6. Rename the automatically generated ViewController to PhotosViewController

## Milestone 2: Hook up the Instagram API
1. In PhotosViewController's viewDidLoad method, fire a network request to the Instagram Popular Endpoint
2. Store the returned array of media in a property

## Milestone 3: Build the Main Photo Feed
1. Add a UITableView to PhotosViewController
2. Set the image of the Image View
3. Remember to reload the table view by calling reloadData when the request finishes


## Video Walkthrough 

Here's a walkthrough of implemented user stories:

<img src='https://github.com/jasmineiris/Instagram/blob/master/Instagram.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while building the app.

## License

    Copyright [2016] [Jasmine Farrell]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
