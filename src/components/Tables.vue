<template>
  <div class="container-fluid">
    <div>
      <vue-good-table
        title="Demo Table"
        :columns="columns"
        :rows="rows"
        :paginate="true"
        :lineNumbers="true"
        styleClass="table table-bordered table-hover"
      />
    </div>
  </div>
</template>

<script>
export default {
  name: "Tables_view",
  data: function() {
    return {
      columns: [
        {
          label: "Name",
          field: "name"
        },
        {
          label: "Age",
          field: "age",
          type: "number",
          html: false
        },
        {
          label: "Created On",
          field: "createdAt",
          type: "date",
          inputFormat: "YYYY-MM-DD",
          outputFormat: "DD-MMM-YYYY"
        },
        {
          label: "Percent",
          field: "score",
          type: "percentage",
          html: false
        }
      ],
      rows: [
        {
          id: 1,
          name: "Khalifa",
          age: 22,
          createdAt: "2022-08-2",
          score: 0.03343
        },
        { id: 1, name: "Malick", age: 32, createdAt: "2022-08-2", score: 0.1 },
        {
          id: 1,
          name: "El Hadji",
          age: 22,
          createdAt: "2022-08-2",
          score: 0.312
        },
        {
          id: 1,
          name: "Israel",
          age: 52,
          createdAt: "2022-08-2",
          score: 0.0764
        },
        { id: 1, name: "Ismael", age: 29, createdAt: "2022-08-2", score: 0.23 },
        {
          id: 1,
          name: "Cheikh",
          age: 65,
          createdAt: "2022-08-2",
          score: 0.0873
        },
        { id: 1, name: "Awa", age: 34, createdAt: "2022-08-2", score: 0.05675 },
        {
          id: 1,
          name: "Fatou",
          age: 23,
          createdAt: "2022-08-2",
          score: 0.02342
        },
        {
          id: 1,
          name: "Maimouna",
          age: 44,
          createdAt: "2022-08-2",
          score: 0.56
        },
        {
          id: 1,
          name: "Aissatou",
          age: 49,
          createdAt: "2022-08-2",
          score: 0.0234
        }
      ]
    };
  }
};
</script>

<style></style>
