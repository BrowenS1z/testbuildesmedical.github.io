<template>
    <div>
        <nav>
            <div class="nav nav-tabs" id="nav-tab" role="tablist">
                <button class="nav-link active" id="nav-home-tab" data-bs-toggle="tab" data-bs-target="#nav-home" type="button" role="tab" aria-controls="nav-home" aria-selected="true">1 Часть</button>
                <button class="nav-link" id="nav-profile-tab" data-bs-toggle="tab" data-bs-target="#nav-profile" type="button" role="tab" aria-controls="nav-profile" aria-selected="false">2 Часть</button>
            </div>
        </nav>

        <div class="tab-content" id="nav-tabContent">
            <div class="tab-pane fade show active" id="nav-home" role="tabpanel" aria-labelledby="nav-home-tab"> <certificate1 /> </div>
            <div class="tab-pane fade" id="nav-profile" role="tabpanel" aria-labelledby="nav-profile-tab"> <certificate2 /> </div>
        </div>
    </div>
</template>

<script>
    import certificate1 from './certificate-Part-1'
    import certificate2 from './certificate-Part-2'

export default {
  name: 'App',
  components: {
    certificate1,
    certificate2
  }
}
</script>

<style>
.certificate{
    margin-top: 30px;
    width: 960px;
    background-color: #fff;
    border-radius: 10px;
    padding: 20px;
    margin-bottom: 30px;
    box-shadow: 0px 1px 2px rgba(0, 0, 0, 0.06), 0px 1px 3px rgba(0, 0, 0, 0.1);
}

.certificate-title{
    font-weight: 600;
}

.certificate-form{
    display: flex;
    margin-top: 5px;
}

.form-floating{
    margin-top: 10px;
    margin-right: 10px;
}

.input-size-lg{
    width: 642px;
}

/* Форма: Пациент */
.Passport{
    justify-content: center;
}

/* Форма: Пациент */
.Patient{
    align-items: center;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
}

.content_form-check{
    display: flex;
    width: 120px;
    justify-content: space-evenly;
    margin-right: 10px;
    margin-top: 10px;
}

/* Форма: Документ, удостоверяющий личность */
.Document-personality{
    flex-wrap: wrap;
    justify-content: center;
}

.organization_that_issued_the_document{
    width: 641px;
}
</style>