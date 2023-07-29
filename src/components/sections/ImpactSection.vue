<template>
  <div class="container p-5 mt-5">
    <h1>Our Programs</h1>
    <div class="row">
      <div class="col-4 mt-5">
        <div class="impact-img">
          <img class="img-fluid" src="@/assets/img.svg" alt="" />
        </div>
        <div class="impact-body mt-5">
          <h1 class="impact-title mt-5">Residential Care</h1>
          <p class="impact-text mt-3">
            We offer safe and comfortable residential facilities where children
            can live and grow in a family-like environment. Our trained and
            compassionate staff members provide round-the-clock care and
            support, ensuring the children's physical and emotional well-being.
          </p>
        </div>
      </div>
      <div class="col-4 mt-5">
        <div class="impact-img">
          <img class="img-fluid" src="@/assets/img.svg" alt="" />
        </div>
        <div class="impact-body mt-5">
          <h1 class="impact-title mt-5">Education and Skill</h1>
          <p class="impact-text mt-3">
            We believe in the power of education to transform lives. Our
            foundation provides quality education to orphaned children, enabling
            them to acquire knowledge, skills, and values necessary for their
            holistic development. We also offer vocational training programs to
            equip older children with practical skills that will help them
            secure a better future.
          </p>
        </div>
      </div>
      <div class="col-4 mt-5">
        <div class="impact-img">
          <img class="img-fluid" src="@/assets/img.svg" alt="" />
        </div>
        <div class="impact-body mt-5">
          <h1 class="impact-title mt-5">Healthcare and Nutrition</h1>
          <p class="impact-text mt-3">
            We prioritize the health and well-being of the children under our
            care. We provide access to regular medical check-ups, vaccinations,
            and necessary healthcare services. Additionally, we ensure that the
            children receive nutritious meals, promoting their growth and
            overall health.
          </p>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col mt-5">
        <div class="impact-img">
          <img class="img-fluid" src="@/assets/img.svg" alt="" />
        </div>
        <div class="impact-body mt-5">
          <h1 class="impact-title mt-5">Psychosocial Support</h1>
          <p class="impact-text mt-3">
            We understand the emotional challenges that orphaned children face.
            Our foundation offers counseling and therapeutic services to help
            them cope with their past traumas, develop resilience, and build
            healthy relationships. We also organize recreational activities and
            outings to encourage social interaction and foster a sense of
            belonging.
          </p>
        </div>
      </div>
      <div class="col mt-5">
        <div class="impact-img">
          <img class="img-fluid" src="@/assets/img.svg" alt="" />
        </div>
        <div class="impact-body mt-5">
          <h1 class="impact-title mt-5">Adoption and Foster Care</h1>
          <p class="impact-text mt-3">
            In collaboration with adoption agencies, we facilitate the adoption
            and foster care process for eligible children, ensuring they find
            loving and permanent families. We prioritize the best interests of
            the child and work closely with potential adoptive parents to ensure
            a smooth transition and provide support throughout the adoption
            journey.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ImpactSection",
};
</script>

<style scoped>
.impact-title {
  color: #000;
  text-align: center;
  font-family: Bebas Neue;
  font-size: 24px;
  font-style: normal;
  font-weight: 400;
  line-height: 30px; /* 125% */
  letter-spacing: 0.3px;
}

.impact-text {
  color: #000;
  text-align: center;
  font-family: Open Sans;
  font-size: 20px;
  font-style: normal;
  font-weight: 400;
  line-height: 30px; /* 150% */
  letter-spacing: 0.3px;
  text-align: start;
}
</style>
