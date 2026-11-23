# DemoProject

![KanbanRaum logo](../favicon.svg)

A sample Kanban workspace for KanbanRaum, with an example product-launch board and dummy work items.

## Start — no Node.js and no server

Open KanbanRaum by opening the parent folder's `index.html` in a current Chromium browser such as Chrome or Edge. Choose this `DemoProject` folder as the workspace. The browser needs the File System Access API and permission to read and write the folder.

## Language

The board names, phases, descriptions, tags, and subtasks in this demo are in English. KanbanRaum's English interface can be loaded by adding `?lang=en` to the app page URL.

## Usage

1. **Open KanbanRaum.** Choose the `DemoProject` folder as the workspace.
2. **Select the board.** Choose **Website Launch** in the sidebar.
3. **Explore the phases.** The board contains **To Do**, **In Progress**, **In Review**, and **Done**.
4. **Open a work item.** The sample tasks include descriptions, priorities, tags, and some subtasks.

The workspace board list is stored in `.kanban-boards.json`. Phase order and colors are stored in `Website Launch/.phases.json`. Work items are regular folders containing a `task.md` file and optional metadata files.

All names and task details are fictional examples. Feel free to edit, move, or delete them while exploring the app.
