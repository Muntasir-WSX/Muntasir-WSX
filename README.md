const Muntasir = {
  name: "Muntasir Mahmud",
  role: "Software Engineer",
  field: "Computer Science & Engineering",

  education: {
    university: "International Islamic University Chittagong",
    degree: "B.Sc. in Computer Science & Engineering",
    status: "Final Year"
  },

  stack: {
    frontend: [
      "JavaScript",
      "TypeScript",
      "React",
      "Next.js",
      "Tailwind CSS"
    ],

    backend: [
      "Node.js",
      "Express.js"
    ],

    database: [
      "MongoDB",
      "PostgreSQL"
    ],

    tools: [
      "Git",
      "GitHub",
      "REST APIs",
      "Prisma"
    ]
  },

  engineering: {
    interests: [
      "Software Architecture",
      "Scalable Systems",
      "Backend Engineering",
      "API Design",
      "Authentication & Authorization",
      "Database Design"
    ]
  },

  exploring: [
    "Generative AI",
    "LLM Integration",
    "RAG",
    "AI-powered Applications",
    "System Design"
  ],

  principles: [
    "Understand the problem first",
    "Write maintainable code",
    "Build scalable systems",
    "Keep learning"
  ],

  goal:
    "Build reliable software and grow into a strong Full-Stack Engineer."
};


console.log("MUNTASIR MAHMUD");
console.log("================");

console.log(`Role       : ${Muntasir.role}`);
console.log(`Field      : ${Muntasir.field}`);

console.log("\nEducation");
console.log("---------");
console.log(`University : ${Muntasir.education.university}`);
console.log(`Degree     : ${Muntasir.education.degree}`);
console.log(`Status     : ${Muntasir.education.status}`);

console.log("\nTechnology");
console.log("----------");

Object.entries(Muntasir.stack).forEach(([category, technologies]) => {
  console.log(
    `${category.padEnd(10)}: ${technologies.join(", ")}`
  );
});

console.log("\nEngineering Interests");
console.log("---------------------");

Muntasir.engineering.interests.forEach((interest) => {
  console.log(`> ${interest}`);
});

console.log("\nCurrently Exploring");
console.log("-------------------");

Muntasir.exploring.forEach((topic) => {
  console.log(`> ${topic}`);
});

console.log("\nEngineering Principles");
console.log("----------------------");

Muntasir.principles.forEach((principle, index) => {
  console.log(`${index + 1}. ${principle}`);
});

console.log("\nGoal");
console.log("----");
console.log(Muntasir.goal);

console.log("\n[ System Status: Learning & Building ]");
