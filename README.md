## 💡 Skills & Expertise

Here are the key technologies and tools I work with:

### 🖥 **Programming Languages & Frameworks**
- **C#** – Building robust and performant applications.
- **.NET** – Leveraging the power of the .NET ecosystem for enterprise-level solutions.
- **JavaScript (Node.js)** – Developing full-stack web applications.

### 🛠 **Databases & Caching**
- **SQL Server** – Expertise in building and optimizing relational database systems.
- **MySQL** – Familiarity with open-source relational databases for scalable applications.
- **Redis** – Utilizing Redis for fast, in-memory data storage and caching.

### 🔒 **Security & Best Practices**
- **OAuth2 / OpenID** – Implementing secure authentication and authorization systems.
- **Encryption** – Ensuring data privacy and security with advanced encryption techniques.
- **Code Reviews & Quality Assurance** – Maintaining high-quality, maintainable code.

### 💻 **Frostvein**
My greatest achievement is my OpenNos fork (An MMORPG Emulator for the Game NosTale), called **Frostvein**. In this project, I migrated to .NET 8.0, reworked core systems, and integrated advanced technologies like Redis and gRPC to enhance performance and scalability. The system is built with a modular plugin architecture, allowing for easy extension and maintenance.

Frostvein is feature-complete, supporting 100% of the systems and approximately 95% of the official algorithms. The project is not only stable and high-performing but also incorporates a wide range of security systems, which have proven to be both functional and highly efficient.

Key components of Frostvein include:

- A Standalone Log Server designed as an API, allowing the World Server to make calls without direct interaction.
- A Service Manager that handles Items, Monsters, NPCs, Guri, Commands and Character Management, ensuring efficient game world processing.
- A dedicated Bazaar, Friendlist, Blacklist, and Mail server, called Communication Server, which communicates through an inter-channel service for seamless operation across different Channels.
- A completely reworked Battle System that performs at an almost identical level to the official servers. It’s backed by an extremely smooth BCard System (pluggable) that can be easily customized to suit different game needs.
- A anti-cheat Service called **Titan Shield**. 
- A proper scripting service utilizing LUA instead of XML. LUA was chosen because it is far more efficient and maintainable than XML, allowing for much easier modification and extension. Unlike XML, which can become cumbersome and difficult to manage for complex systems, LUA provides greater flexibility, performance, and readability. This makes it ideal for handling Raids, TimeSpaces, and specialized Events, where dynamic logic and performance are critical.
- All performance bottlenecks, NullReferenceExceptions (NREs), and other critical issues from OpenNos have been thoroughly identified and reworked, resulting in a significantly optimized and stable system. Frostvein is designed in such a modular and independent way that NREs should no longer occur, as each system operates in isolation, minimizing the risk of unintended dependencies. By addressing these inefficiencies, Frostvein now runs with improved performance, stability, and responsiveness, even under heavy load.
- gRPC-based Server Communication: Instead of the traditional Master Server, Frostvein uses gRPC for efficient, low-latency communication. This allows for real-time synchronization and highly scalable, bidirectional data transfer, making it ideal for MMORPG architecture.
- PostgreSQL Database: Frostvein uses PostgreSQL instead of SQL Server for its advanced features like table partitioning, JSONB support, and custom functions, providing better scalability and flexibility for handling complex game data. Its powerful querying capabilities ensure fast access to critical game information.
- Redis Cache: Redis serves as an in-memory cache, dramatically improving performance by reducing database load and enabling fast data retrieval. It handles real-time features like player sessions, inventory, and dynamic events, ensuring a smooth and responsive gameplay experience.
- Abstract and efficient data access without direct database calls. In Frostvein, i avoided direct database access by implementing a clear separation between data access logic and business logic. Instead of accessing database objects like Session.Character.Level directly, we utilize optimized data access layers and caching mechanisms. This enables more efficient, maintainable code and ensures that data is only loaded or updated when necessary, without unnecessary database queries.

## 🌱 Continuous Learning
I'm always eager to learn new technologies and methodologies to keep my skills sharp and stay ahead in the ever-evolving world of tech. Currently, I'm diving deeper into **cloud-native architectures** and **machine learning**.

## 🌍 About Me

I love tackling complex challenges and transforming them into elegant, working solutions. My goal is to create impactful technology that helps businesses and individuals succeed in their digital journey. Whether it's building scalable systems, optimizing performance, or crafting user-friendly interfaces, I strive for excellence in every project.

Feel free to check out my repositories and contribute to the exciting open-source projects I'm working on.

