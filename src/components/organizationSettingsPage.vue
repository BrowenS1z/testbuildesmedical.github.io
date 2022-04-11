<template>
    <div class="organization">
        <div class="certificate">
            <div class="certificate-title">Настройки организации</div>
            <div class="certificate-form OrganizationSettings">
                <div class="form-floating Name_of_medical_organization">
                    <input type="text" class="form-control" id="floatingInput" placeholder="Наименование медицинской организации">
                    <label for="floatingInput">Наименование медицинской организации</label>
                </div>
                <div class="form-floating mr-40">
                    <input type="text" class="form-control" id="floatingInput" placeholder="ОКУД">
                    <label for="floatingInput">ОКУД</label>
                </div>
                <div class="form-floating mr-40">
                    <input type="text" class="form-control" id="floatingInput" placeholder="ОКПО">
                    <label for="floatingInput">ОКПО</label>
                </div>
                <div class="form-floating mr-11">
                    <input type="text" class="form-control" id="floatingInput" placeholder="ОГРН">
                    <label for="floatingInput">ОГРН</label>
                </div>
                <div class="form-floating License">
                    <input type="text" class="form-control" id="floatingInput" placeholder="Лицензия">
                    <label for="floatingInput">Лицензия</label>
                </div>
                <div class="form-floating address">
                    <input type="text" class="form-control" id="floatingInput" placeholder="Адрес">
                    <label for="floatingInput">Адрес</label>
                </div>
            </div>
        </div>
        <button type="button" class="btn btn-primary btn-lg">Сохранить</button>
    </div>
</template>

<script>

</script>

<style>
.OrganizationSettings{
    flex-wrap: wrap;
    justify-content: center;
}

.Name_of_medical_organization{
    width: 700px;
}

.License{
    width: 700px;
}

.address{
    width: 700px;
}

.mr-40{
    margin-right: 40px;
}

.mr-11{
    margin-right: 11px;
}

.organization button{
    float: right;
}
</style>
