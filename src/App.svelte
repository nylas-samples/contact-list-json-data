<script>
  import ContactList from "@nylas/components-contact-list";
  const staticContacts = [
    {
      emails: [
        {
          email: "tom@brightideas.com"
        }
      ],
      given_name: "Thomas Edison"
    },
    {
      emails: [
        {
          email: "alex@bell.com"
        }
      ],
      given_name: "Alexander Graham Bell"
    },
    {
      emails: [
        {
          email: "al@particletech.com"
        }
      ],
      given_name: "Albert Einstein"
    }
  ];
</script>

<style>
  main {
    font-family: sans-serif;
    text-align: center;
    height: 800px;
  }
</style>

<main>
	<h1>Nylas Contact List</h1>
  <nylas-contact-list contacts={staticContacts}/>
</main>