## Attio Plugin for Dify

**Author:** langgenius  
**Type:** Tool

## Overview | 概述

The **Attio Plugin** connects **Dify** with **Attio** to manage CRM data and automate operations such as listing, creating, updating, and deleting **records**, **objects**, **lists**, and **attributes** in your Attio workspace.

*Attention*: If you need to use filtering and sorting in **List Record** / **List Entries**, please view rules [here](https://attio.mintlify.app/rest-api/how-to/filtering-and-sorting). You can create agents to help you with that.

-----

Attio 插件将 **Dify** 与 **Attio** 连接起来，用于管理 CRM 数据并自动化操作，例如在您的 Attio 工作区中列出、创建、更新和删除**记录**、**对象**、**列表**和**属性**。

*注意*: 如果您需要在 **List Record** / **List Entries** 中使用过滤和排序，请在此处查看规则 [here](https://attio.mintlify.app/rest-api/how-to/filtering-and-sorting)。您可以创建代理来帮助您完成此操作。

-----

## Features | 功能

  - List, create, update, and delete **records** in Attio objects and lists.
  - Retrieve and manage Attio **objects**, **lists**, and their **attributes**.
  - Filter, sort, and paginate records and entries.
  - Secure API token authentication.

-----

  - 在 Attio 对象和列表中列出、创建、更新和删除**记录**。
  - 检索和管理 Attio **对象**、**列表**及其**属性**。
  - 过滤、排序和分页记录和条目。
  - 安全的 API 令牌认证。

-----

## Usage | 使用

Each tool is defined by a YAML file in the `tools/` directory and implemented in the corresponding Python file. You can invoke these tools from Dify workflows or via API calls.

### Available Tools | 可用工具

The Attio Plugin includes the following tools:

  - **add\_records**: Add one or more records to an Attio object.
  - **list\_records**: List all records in an Attio object, with optional filters and sorting.
  - **delete\_records**: Delete a record from an Attio object.
  - **list\_objects**: List all objects in Attio.
  - **create\_objects**: Create a new object in Attio.
  - **list\_lists**: List all lists in Attio.
  - **list\_entries**: List all entries in an Attio list, with optional filters and sorting.
  - **add\_entries**: Add entries to an Attio list.
  - **delete\_entries**: Delete an entry from an Attio list.
  - **list\_attributes**: List all attributes for a given Attio object or list.

Each tool's YAML file documents the required and optional parameters.

-----

每个工具都在 `tools/` 目录中由一个 YAML 文件定义，并在相应的 Python 文件中实现。您可以从 Dify 工作流或通过 API 调用来调用这些工具。

Attio 插件包含以下工具：

  - **add\_records**: 向 Attio 对象添加一个或多个记录。
  - **list\_records**: 列出 Attio 对象中的所有记录，可选择过滤和排序。
  - **delete\_records**: 从 Attio 对象中删除一条记录。
  - **list\_objects**: 列出 Attio 中的所有对象。
  - **create\_objects**: 在 Attio 中创建一个新对象。
  - **list\_lists**: 列出 Attio 中的所有列表。
  - **list\_entries**: 列出 Attio 列表中的所有条目，可选择过滤和排序。
  - **add\_entries**: 向 Attio 列表添加条目。
  - **delete\_entries**: 从 Attio 列表中删除一个条目。
  - **list\_attributes**: 列出给定 Attio 对象或列表的所有属性。

每个工具的 YAML 文件都记录了必需和可选的参数。

-----

## Issue Feedback | 问题反馈

For more detailed information on plugin development, see [GUIDE.md](https://www.google.com/search?q=./GUIDE.md).

Several functions are under active development, including **Add Entries**, **Delete Entries**, and **Create Object**. You might encounter some bugs when using these specific functions.

-----

有关插件开发的更多详细信息，请参阅 [GUIDE.md](https://www.google.com/search?q=./GUIDE.md)。

一些功能正在积极开发中，包括 **Add Entries**、**Delete Entries** 和 **Create Object**。使用这些特定功能时，您可能会遇到一些错误。