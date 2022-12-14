### Features
    - User Account Features
    - CRUD functionality for todo
    - Change Order by dragging each todo
    - Search feature
    - Detail Modal
        - Due date
        - Rich text editor for notes
        - Attach image items
        - create workflows

    Add Later

        - share workflows with others
        - add tags for each todo
        - send email to user end of every month with InSights
        - send summary email to user about tasks


front page - https://www.canva.com/graphs/flowcharts/
for mind maps - https://gojs.net/latest/samples/mindMap.html

- Workflow - App development project
  - List - UI design
    - Todo Items
  - List - Front end development
    - Todo Items
  - List - Front end Q/A
    - Todo Items
  - List - Back end development
    - Todo Items
  - List - Back end Q/A
    - Deploy

### TODO

- [ ] - Static Landing Page

- [x] - UI/UX
  - [x] - Add Progress bar
  - [x] - Todo page
  - [x] - Todo Modal View
  - [x] - Settings page
  - [x] - Workflow Page
- [ ] - Create login pages
  - [ ] - federated identity login with cognito user pool SDK
- [ ] - build a beautiful website for app

- [ ] - Build Todo Page
  - [x] - Setup the filesystem
  - [ ] - Build the layout
  - [ ] - Read the Frontend Architecture Guide
  - [ ] - Modal
  - [ ] - Todo Components
  - [ ] - Draggable effect
  - [ ] - Learn canvas styling and improve the flow building UI

- [x] - Modal the dataset

- [/] - Learn AWS lambda functions
- [ ] - Learn API Gateway
- [ ] - Learn TypeScript in Lambda
- [ ] - come up with good architecture for handle API in serverless


- [ ] - Experiments for more learning
  - [ ] - Learn to do redux CRUD and api fetching without RTK (Vanilla Redux)
  - [ ] - https://github.com/piotrwitek - read his code

- Workflow Entity
  - ID
  - Name - String
  - Tasks - Array (FK)

- Task Entity
  - ID
  - Name - String
  - Task Items - Array
  - Key - number
  - KeyTo - number
  - KeyFrom - number
  - TaskItems - Array (FK)

- Task Item
  - ID
  - Title - String
  - Description - String
  - Due Date - String
  - Attachments - Array
  - IsCompleted - Boolean