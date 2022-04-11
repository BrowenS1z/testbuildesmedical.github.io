<template>
    <div class="doctors">
        <div class="doctors_actions">
            <div class="doctors_add">
                <button type="button" id="myModal" class="btn btn-outline-primary btn-lg">+ Добавить</button>
            </div>
            <div class="doctors_search">
                <div class="container-fluid">
                    <form class="d-flex">
                        <input class="form-control me-2" type="search" placeholder="Введите текст для поиска" aria-label="Search">
                        <button class="btn btn-outline-success" type="submit">Поиск</button>
                    </form>
                </div>
            </div>
        </div>

        <div class="modal-dialog modal-dialog-centered" id="modal-template">
        ...
        </div>

        <div class="doctors_table">
            <table class="table">
                <thead>
                    <tr>
                        <th scope="col">ФИО специалиста</th>
                        <th scope="col">Специальность</th>
                        <th scope="col"></th>
                        <th scope="col"></th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Иванов Иван Иванович</td>
                        <td>Врач-терапевт</td>
                        <td class="action"><a href="#" class="btn btn-outline-success btn-edit" data-bs-toggle="tooltip" data-bs-placement="top" title="Редактировать"><span class="material-icons">edit</span></a></td>
                        <td class="action"><a href="#" class="btn btn-outline-danger btn-edit" data-bs-toggle="tooltip" data-bs-placement="top" title="Удалить"><span class="material-icons">delete</span></a></td>
                    </tr>
                    <tr>
                        <td>Смирнов Николай Иванович</td>
                        <td>Врач-терапевт</td>
                        <td class="action"><a href="#" class="btn btn-outline-success btn-edit" data-bs-toggle="tooltip" data-bs-placement="top" title="Редактировать"><span class="material-icons">edit</span></a></td>
                        <td class="action"><a href="#" class="btn btn-outline-danger btn-edit" data-bs-toggle="tooltip" data-bs-placement="top" title="Удалить"><span class="material-icons">delete</span></a></td>
                    </tr>
                </tbody>
            </table>
        </div>
    </div>
</template>

<script>

</script>

<style>
.doctors{
    width: 960px;
    margin-top: 20px;
}
.doctors_actions{
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.d-flex input{
    width: 240px;
}

.doctors_table{
    margin-top: 30px;
}

.btn-edit{
    width: 34px;
    height: 34px;
    display: flex;
    align-items: center;
    justify-content: center;
}
.action{
    width: 40px;
}
</style>
