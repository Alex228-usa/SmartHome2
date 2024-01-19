<template>
    <footer>
      <div class="footer-content">
        <div class="contact-info">
          <p>Телефон: {{ phoneNumber }}</p>
        </div>
      </div>
    </footer>
</template>
  
<script>
export default {
    name: 'FooterComp',
    data() {
        return {
            phoneNumber: '+7 771 371 52 55',

        }
    }
}
</script>

<style scoped>
footer {
    background-color: #1C2323;
    color: #fff;
    text-align: center;
    padding: 20px;
    border-radius: 10px;
}

.footer-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 20px;
}

.contact-info {
    text-align: left;
}

.social-links {
    display: flex;
}

.social-links a {
    color: #fff;
    margin-right: 10px;
    text-decoration: none;
}

.social-links img {
    width: 35px;
}

.social-links-a {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.social-links a:hover {
    text-decoration: underline;
}
</style>