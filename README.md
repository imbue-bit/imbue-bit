我是初中生，所以在处理 pull requests 与 issues 时也许效率会很低，见谅。:)

I'm a junior high school student, so I might be quite inefficient when dealing with pull requests and issues. Please excuse me. :)

```C
#include <stdio.h>

struct Skills {
    struct Languages {
        const char* proficient[6];
        const char* familiar[4];
        const char* exploring[5];
    } languages;

    struct Frontend {
        const char* frameworks_libraries[4];
        const char* styling[5];
        const char* state_management[3];
        const char* tools[3];
    } frontend;

    struct Backend {
        const char* frameworks_runtime[4];
        const char* databases[4];
        const char* orms[3];
        const char* apis[2];
    } backend;
    
    struct DataScience {
        const char* libraries[2];
        const char* tools[2];
    } data_science;

    struct DevOpsAndCloud {
        const char* containerization[2];
        const char* ci_cd[1];
        const char* cloud_platforms[3];
    } devops;

    struct ToolsAndEnvironment {
        const char* version_control[2];
        const char* editors_ides[3];
        const char* operating_systems[3];
        const char* design_tools[2];
    } tools;
};

struct AboutMe {
    const char* name;
    const int age;
    const char* gender;
    const char* interests[5];
    struct Skills skills;
};

struct AboutMe me = {
    .name = "imbue",
    .age = 14,
    .gender = "Female",
    .interests = {
        "Competitive Programming",
        "Full-Stack Development",
        "Open Source Contribution",
        "UI/UX Design",
        "Algorithm Design"
    },
    .skills = {
        .languages = {
            .proficient = { "C++", "Python", "JavaScript", "TypeScript", "HTML5", "CSS3" },
            .familiar = { "Rust", "Go", "Java", "SQL" },
            .exploring = { "Haskell", "Lisp", "C", "x86 Assembly", "QASM" }
        },
        .frontend = {
            .frameworks_libraries = { "React", "Next.js", "Vue.js", "Svelte" },
            .styling = { "Tailwind CSS", "Sass/SCSS", "Bootstrap", "Material-UI", "Styled-components" },
            .state_management = { "Redux", "Zustand", "Pinia" },
            .tools = { "Vite", "Webpack", "Babel" }
        },
        .backend = {
            .frameworks_runtime = { "Node.js", "Express.js", "FastAPI (Python)", "Actix Web (Rust)" },
            .databases = { "PostgreSQL", "MySQL", "MongoDB", "Redis" },
            .orms = { "Prisma", "SQLAlchemy (Python)", "Sequelize" },
            .apis = { "RESTful APIs", "GraphQL (Apollo)" }
        },
        .data_science = {
            .libraries = { "Python (NumPy, Pandas, Matplotlib, Scikit-learn)", "R (ggplot2)" },
            .tools = { "Jupyter Notebook", "SQL" }
        },
        .devops = {
            .containerization = { "Docker", "Docker Compose" },
            .ci_cd = { "GitHub Actions" },
            .cloud_platforms = { "Vercel", "Netlify", "AWS (EC2, S3) - Basic" }
        },
        .tools = {
            .version_control = { "Git", "GitHub" },
            .editors_ides = { "VS Code", "Neovim", "JetBrains IDEs" },
            .operating_systems = { "Linux (Ubuntu, Arch, CentOS, Rocky Linux)", "Windows (with WSL2)", "macOS" },
            .design_tools = { "Figma", "Adobe XD" }
        }
    }
};
```

---

[![Readme Quotes](https://quotes-github-readme.vercel.app/api?quote=%E7%A7%91%E7%BD%97%E5%BB%96%E5%A4%AB%E5%8D%81%E5%AD%97%E7%BB%BD%E5%BC%80%EF%BC%8C%E6%88%91%E6%98%AF%E5%8D%A1%E9%97%A8%E7%BA%BF%E4%B8%8A%E7%9A%84%E8%8A%B1&type=horizontal&theme=dark)](https://github.com/piyushsuthar/github-readme-quotes)

<img src="https://github-readme-activity-graph.vercel.app/graph?username=imbue-bit" />

---

# Index Of /
