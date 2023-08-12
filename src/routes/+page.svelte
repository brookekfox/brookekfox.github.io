<script lang="ts">
  import WorkExperience from "../lib/components/WorkExperience.svelte";
  import Certificate from "../lib/components/Certificate.svelte";
  import Education from "../lib/components/Education.svelte";
  import louie from "./images/louie.png";

  const aoflDescription =
    "Led the backend development of several AofL flagship products, including ReadingIQ, ABCmouse English, and My Reading Academy. Responsible for the LiveOps of ReadingIQ, ABCmouse English, and My Reading Academy. Developed microservice architecture for high-traffic APIs for consumer and enterprise customers. Designed database schema. Contributed to product development and technology decisions for the department. Provided code reviews and feedback to other engineers. Developed CI/CD including unit testing, code quality, security scanning, deployment, etc. Developed deployment infrastructure and workflow. Managed shared templates for CI/CD and infrastructure as code. Wrote documentation and developed training course for new or cross-training developers. Mentored lower level engineers. Trained QA and other engineers. Interviewed junior and mid-level software engineers and QA.";
  const aoflDescriptionSecondary =
    "Started as an associate software engineer and was promoted to software engineer I, software engineer II, software engineer III, and senior software engineer within 5 1/2 years.";
  const nauDescription =
    "Prepared and delivered class lectures, homework assignments, and exams in computer-based and traditional, lecture-based settings as the primary instructor. Met with students outside of class. Supervised undergraduate tutors and TAs. Attended weekly course coordination meetings. Administered all grades. Two sections per semester of MAT100 Mathematics Pathway, MAT119 Finite Mathematics, and/or MAT125 Precalculus.";
</script>

<main
  class="flex flex-col justify-center align-middle items-center p-4 md:p-16"
>
  <div class="border-2 border-primary w-full mb-6 md:mb-12">
    <div
      class="text-primary p-4 w-full border-1 border-primary bg-accent-2 flex md:flex-row flex-col justify-between align-middle items-center"
    >
      <h1 class="font-bold text-3xl mb-2 md:mb-0">Brooke Fox</h1>
      <span class="italic text-sm md:text-xs mb-2 md:mb-0"
        >Staff Software Engineer</span
      >
      <div
        class="text-xs flex flex-col justify-evenly align-middle items-center md:items-end"
      >
        <span class="mr-2 md:mr-0"
          ><a href="mailto:brookekfox@gmail.com">
            brooke.k.fox@gmail.com
          </a></span
        >
        <span class="mr-2 md:mr-0">602.463.4440</span>
        <span class="mr-2 md:mr-0">Los Angeles, CA</span>
      </div>
    </div>

    <div
      class="text-xs text-primary p-4 flex flex-row justify-center items-center align-middle w-full"
    >
      Driven and efficient software engineer focused on building backend
      solutions, including APIs, infrastructure as code, and CI/CD.
    </div>
  </div>

  <div class="border-2 border-primary w-full mb-6 md:mb-12">
    <div
      class="text-primary p-4 w-full border-1 border-primary bg-accent-2 flex flex-col md:flex-row justify-between align-middle items-center"
    >
      <h2 class="font-bold text-2xl">Work Experience</h2>
    </div>
    <div
      class="text-primary w-full border-1 border-primary flex flex-row flex-wrap justify-between align-middle items-center"
    >
      <WorkExperience
        company="Age of Learning"
        location="Glendale, CA"
        startDate="Jan 2017"
        position="Staff Software Engineer"
        description={aoflDescription}
        descriptionSecondary={aoflDescriptionSecondary}
        technologies="PHP, PHPUnit, Docker, Kubernetes, SQL, NoSQL, Google Protcol Buffers, AWS Cloud Infrastructure, infrastructure as code, Gitlab pipelines, Jenkins, Typescript, web components, Svelte, Dart, Flutter, Go, Bash"
      />
      <WorkExperience
        company="Logical Reality Design"
        location="Pasadena, CA"
        startDate="Apr 2015"
        endDate="Oct 2015"
        position="Mid Level Full Stack Developer"
        description="Developed full-stack web applications in Ruby on Rails shop. Implemented unit, integration, and UI tests."
        technologies="Ruby, Ruby on Rails, PostgreSQL, JavaScript, Angular, rspec, Cabybara, Selenium"
      />
    </div>
  </div>

  <div class="border-2 border-primary w-full mb-6 md:mb-12">
    <div
      class="text-primary p-4 w-full border-1 border-primary bg-accent-2 flex flex-col md:flex-row justify-between align-middle items-center"
    >
      <h2 class="font-bold text-2xl">Certificates</h2>
    </div>
    <div
      class="text-primary w-full border-1 border-primary flex flex-row flex-wrap justify-evenly align-middle items-center"
    >
      <Certificate
        title="AWS Database Solutions"
        date="Oct 2022"
        description="AWS instructor-led class"
      />
      <Certificate
        title="AWS Solutions architecture"
        date="Oct 2021"
        description="AWS instructor-led class"
      />
      <Certificate
        title="Web Development Bootcamp"
        date="Apr 2015"
        description="General Assembly, Santa Monica, CA"
      />
    </div>
  </div>

  <div class="border-2 border-primary w-full mb-6 md:mb-12">
    <div
      class="text-primary p-4 w-full border-1 border-primary bg-accent-2 flex justify-between align-middle items-center"
    >
      <h2 class="font-bold text-2xl">Education</h2>
      <!-- <img
        src={louie}
        class="h-12"
        alt="Northern Arizona University Louie the Lumberjack logo"
      /> -->
    </div>
    <div
      class="text-primary w-full border-1 border-primary flex flex-col justify-start align-middle items-center mr-2"
    >
      <Education
        school="Northern Arizona University"
        location="Flagstaff, AZ"
        graduationDate="May 2014"
        degree="MS in Mathematics"
      />
      <Education
        school="Northern Arizona University"
        location="Flagstaff, AZ"
        graduationDate="May 2012"
        degree="BS in Mathematics with an emphasis in pure mathematics"
      />
    </div>
  </div>

  <div class="border-2 border-primary w-full mb-6 md:mb-12">
    <div
      class="text-primary p-4 w-full border-1 border-primary bg-accent-2 flex flex-col md:flex-row justify-between align-middle items-center"
    >
      <h2 class="font-bold text-2xl">Other Work Experience</h2>
    </div>
    <div
      class="text-primary w-full border-1 border-primary flex flex-row flex-wrap justify-between align-middle items-center"
    >
      <WorkExperience
        company="STAR Prep Academy"
        location="Los Angeles, CA"
        startDate="Dec 2015"
        endDate="Dec 2016"
        position="High School Mathematics Teacher"
        description="Taught 9th through 12th grade mathematics (Algebra 1 through Calculus). Taught web development and physical education electives. Supervised field trips, service projects, and overnight trips."
      />
      <WorkExperience
        company="Northern Arizona University"
        location="Flagstaff, AZ"
        startDate="Aug 2012"
        endDate="May 2014"
        position="Graduate Teaching Instructor"
        description={nauDescription}
      />
    </div>
  </div>

  <div class="border-2 border-primary w-full mb-6 md:mb-12">
    <div
      class="text-primary p-4 w-full border-1 border-primary bg-accent-2 flex flex-col md:flex-row justify-between align-middle items-center"
    >
      <h2 class="font-bold text-2xl">Community</h2>
    </div>
    <div
      class="text-primary p-4 w-full border-1 border-primary flex flex-col justify-start align-middle items-center"
    >
      <WorkExperience
        company="Gemmed"
        location="Los Angeles, CA"
        startDate="2019"
        position="Executive board member"
        description="Non-profit providing eating disorder group therapy"
      />
    </div>
  </div>
</main>
