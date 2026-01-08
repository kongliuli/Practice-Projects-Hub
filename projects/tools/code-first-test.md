# CodeFirstTest - 数据库 Code First 模式测试

## 核心需求
开发一个小型项目，用于测试和演示数据库 Code First 开发模式，主要包括：
1.  **实体定义**：通过 C# 类定义数据库实体模型。
2.  **上下文配置**：配置 `DbContext`，连接数据库。
3.  **迁移管理**：演示如何创建、应用和回滚数据库迁移。
4.  **CRUD 操作**：实现基本的增删改查操作，验证数据持久化。

## 开发目标
-   验证 Code First 模式在不同数据库（如 SQL Server, SQLite）上的兼容性。
-   为其他项目提供 Code First 实践的参考示例。

## 建议技术栈
-   **语言**: C#
-   **框架**: .NET 8 (或更高版本)
-   **UI**: WinForms (用于简单的界面展示和操作) 或 Console Application (纯逻辑演示)
-   **ORM**: Entity Framework Core
-   **数据库**: SQL Server LocalDB 或 SQLite

## Solo 模式开发提示
-   **指令示例**: "创建一个 Code First 项目，定义一个 User 实体，包含 Id, Name, Email 字段，并实现其 CRUD 操作。"
-   **关注点**: 优先关注 EF Core 的配置和实体映射，UI 界面保持极简。
