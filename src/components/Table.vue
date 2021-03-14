<template>
    <div class="table">
        <div class="title-select">
            <h1>Цены за АЗС </h1>

            <select id="city" name="city" form="cityform">
                <option value="Almaty">Выберите город</option>
                <option value="Aqtau">Almaty</option>
                <option value="Astana">Astana</option>
                <option value="Aqtau">Aqtau</option>
                <option value="Shymkent">Shymkent</option>
            </select>
        </div>
    <table class="blueTable">
        <thead>
            <tr>
                <th></th>
                <th>АИ-92</th>
                <th>АИ-95</th>
                <th>АИ-98</th>
                <th>ДТ</th>
            </tr>
        </thead>
    <tbody>
        <tr>
        <td>SINOOIL</td><td>150 тг</td><td>160 тг</td><td>170 тг</td><td>150 тг</td></tr>
        <tr>
        <td>Helios</td><td>151 тг</td><td>158 тг</td><td>171 тг</td><td>150 тг</td></tr>
        <tr>
        <td>KazMunaigaz</td><td>145 тг</td><td>162 тг</td><td>171 тг</td><td>150 тг</td></tr>
        <tr>
        <td>Gazprom</td><td>153 тг</td><td>163 тг</td><td>169 тг</td><td>150 тг</td></tr>
        <tr>
        <td>Royal Petrol</td><td>154 тг</td><td>164 тг</td><td>172 тг</td><td>150 тг</td></tr>
    </tbody>
    </table>
    </div>
</template>


<script>
export default {
    name: 'Table'
}
</script>


<style>
    .table{
        margin-top: 2rem;
    }
 .table h1{
        text-transform: uppercase;
        font-weight: bold;
        color: white;
        font-size: 1rem;
        letter-spacing: 2px;
        font-weight: bold;
    }

    .title-select{
        display: flex;
    }
    select{
        margin-left: 1rem;
        padding: 0.5rem 1rem;
        color: #00a847;
        outline: none;
        font-size: 1rem;
        font-weight: bolder;
    }
    table.blueTable {
        margin-top: 5px;
    border: 0.1px solid #FFF9FC;
    background-color: #22223a;
    width: 100%;
    border-collapse: collapse;
    color: white;
    padding: 1rem;
    }
    table.blueTable td, table.blueTable th {
    border-bottom: 1px solid #AAAAAA;
    padding: 1rem;
    text-align: start;
    }
    

    table.blueTable tbody td {
    font-size: 1rem;
    }
    table.blueTable thead {
    background: #22223a;
    }
    table.blueTable thead th {
    font-size: 1rem;
    font-weight: bold;
    color: #ffffff;
    }
    
</style>