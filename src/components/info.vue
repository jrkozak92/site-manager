<template>
  <div class="component">
    <p>This project will eventually be a full-stack single page application that serves any other projects of my creation that I want to show in this portfolio. 
    Links to these projects will be found in their own individual cards in the 'Database' tab (name subject to change), but they do not exist yet.</p>
    <br/>
    <p>This application, which I'm calling site-manager, is built in Vue.js using Axios and Vue-Router to serve components (and eventually persistent data from a database), running on GitHub Pages using a custom domain, 
    which was surprisingly complex to get a single page app running on, and I am currently developing the backend using Node/Express on an Amazon Web Services (AWS) EC2 
    in conjunction with an AWS RDS PostgreSQL database instance.</p>
    <br/>
    <p>Knowing what I know now, if I were to start this project from scratch I would likely use something other than GitHub Pages (would probably start with more 
    research into Netlify), as it apparently is only meant to serve static sites, but I wanted to get some exposure to the GitHub ecosystem and this certainly 
    presented me with plenty of challenges to troubleshoot which have allowed me to gain a bit more than my previous cursory familiarity. These are the same reasons I am building out the backend using AWS. I previously 
    had no exposure to that suite of technology, but this seems as good an opportunity as any to take that plunge, and I'm sure it will pay off in the same way.</p>
    <br/>
    <p>I plan to continue to update this section of the project as I make progress, at least until the database connection is functional and able to serve up links to 
    and descriptions of other/future projects.</p>
    <br/>
    <p>On the off chance you found this site unprompted, or if its purpose is still unclear, I am building it as an example of my development ability in search of employment 
    as a (likely Junior) Developer, full-stack or otherwise. I understand that if you have found this site without my resume, you don't have my contact information.
     I may add a contact form for this case in the future, but in the meantime, you are welcome to message me directly on <a href="https://www.linkedin.com/in/joseph-kozak-77539189/" style="text-decoration:underline;" target="_blank">LinkedIn</a>.</p>
  </div>
</template>

<script>
// import DataService from "../services/DataService";

export default {
  name: 'info',
  data () {
    return {
        publicPath: process.env.BASE_URL
    }
  }  
}
</script>
