<template>
  <v-layout
    column
    justify-center
    align-center
  >
    <v-flex
      xs12
      sm8
      md6
    >
      <span>kl security systems </span>
      <br />
     
    </v-flex>
  </v-layout>
</template>

<script>

export default {
  
  data() {
       return {
         structuredData: {
                "@context": "https://schema.org",
            "@type": "WebSite",
            "url": "https://klsecuritysystems.com",
            "name": "klsecuritysystems",
         },
       }
     },
     head() {
       return {
         __dangerouslyDisableSanitizers: ['script'],
         script: [{ innerHTML: JSON.stringify(this.structuredData), type: 'application/ld+json' }],
         title: 'klsecurity systems',
           meta: [

           { name: 'viewport', content: 'width=device-width, initial-scale=1' },
           { hid: 'keywords', name: 'keywords',content: 'klsecurity systems' },
           { hid: 'description', name: 'description', content: 'klsecurity systems.' },
           { property:'og:locale' , content:'af-ZA' },
           { property:'og:type' ,content:'website' },
           { property:'og:title' ,content:'klsecurity systems' },
           { property: 'og:description' ,content:' klsecurity systems' },
           { property:'og:site_name' ,content:'klsecurity systems' },
           { property:'og:url' ,content: 'https://bihogoo.com/'},
           {name:'twitter:card' ,content: 'summary_large_card'},
           {name:'twitter:description', content:' klsecurity systems'},
           { name:'twitter:creator' ,content: '@bihogoo.com'},
           {name: 'twitter:site', content: '@bihogo_partners'},
           { name:'twitter:title', content:'klsecurity systems'},
           { name:'twitter:image', content:'https://source.unsplash.com/CiMITAJtb6I'},
         ],
       }
     },
}
</script>
<style>
  </style>
