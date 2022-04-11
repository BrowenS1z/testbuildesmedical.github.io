<template>
    <div>
<!-- Форма Справка -->
        <div class="certificate">
            <div class="certificate-title">Справка</div>
            <div class="certificate-form Passport">
                <div class="form-floating">
                    <input type="text" class="form-control" id="floatingInput" placeholder="Серия">
                    <label for="floatingInput">Серия</label>
                </div>
                <div class="form-floating">
                    <input type="text" class="form-control" id="floatingInput" placeholder="Номер">
                    <label for="floatingInput">Номер</label>
                </div>
                <div class="form-floating">
                    <input type="text" class="form-control" id="floatingInput" placeholder="Дата выдачи">
                    <label for="floatingInput">Дата выдачи</label>
                </div>
            </div>
        </div>
<!-- Форма Пациент -->
        <div class="certificate">
            <div class="certificate-title">Пациент</div>
            <div class="certificate-form Patient">
                <div class="form-floating">
                    <input type="text" class="form-control" id="floatingInput" placeholder="Фамилия">
                    <label for="floatingInput">Фамилия</label>
                </div>
                <div class="form-floating">
                    <input type="text" class="form-control" id="floatingInput" placeholder="Имя">
                    <label for="floatingInput">Имя</label>
                </div>
                <div class="form-floating">
                    <input type="text" class="form-control" id="floatingInput" placeholder="Отчество">
                    <label for="floatingInput">Отчество</label>
                </div>
                <div class="form-floating">
                    <input type="text" class="form-control" id="floatingInput" placeholder="Дата рождения">
                    <label for="floatingInput">Дата рождения</label>
                </div>
                <div class="content_form-check">
                    <div class="form-check">
                        <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault1">
                        <label class="form-check-label" for="flexRadioDefault1">
                            М
                        </label>
                    </div>
                    <div class="form-check">
                        <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault2" checked>
                        <label class="form-check-label" for="flexRadioDefault2">
                            Ж
                        </label>
                    </div>
                </div>
                <div class="form-floating">
                    <input type="text" class="form-control" id="floatingInput" placeholder="СНИЛС" maxlength="11">
                    <label for="floatingInput">СНИЛС</label>
                </div>
                <div class="form-floating">
                    <input type="text" class="form-control" id="floatingInput" placeholder="Социальный статус">
                    <label for="floatingInput">Социальный статус</label>
                </div>
                <div class="form-floating">
                    <input type="text" class="form-control" id="floatingInput" placeholder="Группа инвалидности">
                    <label for="floatingInput">Группа инвалидности</label>
                </div>
            </div>
        </div>
<!-- Форма Пациент -->
        <div class="certificate">
            <div class="certificate-title">Документ, удостоверяющий личность</div>
            <div class="certificate-form Document-personality">
                <div class="form-floating">
                    <input type="text" class="form-control" id="floatingInput" placeholder="Наименование">
                    <label for="floatingInput">Наименование</label>
                </div>
                <div class="form-floating">
                    <input type="text" class="form-control" id="floatingInput" placeholder="Серия">
                    <label for="floatingInput">Серия</label>
                </div>
                <div class="form-floating">
                    <input type="text" class="form-control" id="floatingInput" placeholder="Номер">
                    <label for="floatingInput">Номер</label>
                </div>
                <div class="form-floating organization_that_issued_the_document">
                    <input type="text" class="form-control" id="floatingInput" placeholder="Организация, выдавшая документ">
                    <label for="floatingInput">Организация, выдавшая документ</label>
                </div>
            </div>
        </div>
        <button type="button" class="btn btn-primary btn-lg">Сохранить</button>
    </div>
</template>

<script>

</script>

<style>

</style>
