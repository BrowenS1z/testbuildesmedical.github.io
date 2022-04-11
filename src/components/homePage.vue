<template>
    <div class="wrapper">
        <nav class="navbar navbar-dark bg-primary">
            <div class="authUsers">Шеинов М.Б.</div>
            <div class="exit"><a href="#" type="submit" class="exit-btn">Выход</a></div>
        </nav>

        <ul class="nav nav-pills mb-3" id="pills-tab" role="tablist">
            <li class="nav-item" role="presentation">
                <button class="nav-link active" id="pills-journal-tab" data-bs-toggle="pill" data-bs-target="#pills-journal" type="button" role="tab" aria-controls="pills-journal" aria-selected="true">Журнал выданных справок</button>
            </li>
            <li class="nav-item" role="presentation">
                <button class="nav-link" id="pills-certificate-tab" data-bs-toggle="pill" data-bs-target="#pills-certificate" type="button" role="tab" aria-controls="pills-certificate" aria-selected="false">Новая справка</button>
            </li>
            <li class="nav-item" role="presentation">
                <button class="nav-link" id="pills-doctors-tab" data-bs-toggle="pill" data-bs-target="#pills-doctors" type="button" role="tab" aria-controls="pills-doctors" aria-selected="false">Врачи</button>
            </li>
            <li class="nav-item" role="presentation">
                <button class="nav-link" id="pills-settings-tab" data-bs-toggle="pill" data-bs-target="#pills-settings" type="button" role="tab" aria-controls="pills-settings" aria-selected="false">Настройки организации</button>
            </li>
        </ul>

        <div class="tab-content" id="pills-tabContent">
            <div class="tab-pane fade show active" id="pills-journal" role="tabpanel" aria-labelledby="pills-journal-tab"> <journalPage /> </div>
            <div class="tab-pane fade" id="pills-certificate" role="tabpanel" aria-labelledby="pills-certificate-tab"> <certificatePage /> </div>
            <div class="tab-pane fade" id="pills-doctors" role="tabpanel" aria-labelledby="pills-doctors-tab"> <doctors /> </div>
            <div class="tab-pane fade" id="pills-settings" role="tabpanel" aria-labelledby="pills-settings-tab"> <OrganizationSettings /> </div>
        </div>
        
    </div>
</template>

<script>
import journalPage from './journalPage'
import certificatePage from './certificatePage'
import doctors from './doctorsPage'
import OrganizationSettings from './organizationSettingsPage'


export default {
  name: 'App',
  components: {
    journalPage,
    certificatePage,
    doctors,
    OrganizationSettings
  }
}
</script>

<style>
.wrapper{
    display: flex;
    flex-direction: column;
    align-items: center;
}

.navbar{
    width: 100%;
    color: #fff;
    padding: 20px 40px 20px 40px;
    font-weight: 700;
    font-size: 22px;
}

.exit-btn{
    color: #fff;
    text-decoration: none;
}

.exit-btn:hover{
    color: rgba(255, 255, 255, 0.685);
}

.nav-pills{
    margin-top: 40px;
}

.nav-link{
    width: 240px;
}
</style>