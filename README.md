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

https://github.com/piotrwitek/react-redux-typescript-guide#react--redux-in-typescript---complete-guide
https://redux-toolkit.js.org/introduction/getting-started#installation
https://react-typescript-cheatsheet.netlify.app/docs/basic/getting-started/hooks

serverless with typescript - https://github.com/serverless/typescript

- [ ] - Build Todo Page
  - [x] - Setup the filesystem
    - [ ] - first write js then add types 🌟
  - [ ] - Build the layout
  - [ ] - Read the Frontend Architecture Guide
  - [ ] - Modal
  - [ ] - Todo Components
  - [ ] - Draggable effect
  - [ ] - Learn canvas styling and improve the flow building UI

- [x] - Modal the dataset

- [x] - Learn AWS lambda functions
- [x] - Learn Serverless Framework
- [ ] - Learn API Gateway
- [ ] - Learn to setup typescript project
- [ ] - Learn TypeScript in Lambda
- [ ] - come up with good architecture for handle API in serverless

- [ ] - add serverless offline

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