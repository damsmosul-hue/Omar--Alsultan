<div class="date-selects">
  <!-- السنة على اليسار -->
  <select id="year">
    <option value="">السنة</option>
    <script>
      for(let y=2000; y<=2030; y++){
        document.write(`<option value="${y}">${y}</option>`);
      }
    </script>
  </select>

  <!-- الشهر في الوسط -->
  <select id="month">
    <option value="">الشهر</option>
    <script>
      for(let m=1; m<=12; m++){
        document.write(`<option value="${m}">${m}</option>`);
      }
    </script>
  </select>

  <!-- اليوم على اليمين -->
  <select id="day">
    <option value="">اليوم</option>
    <script>
      for(let d=1; d<=31; d++){
        document.write(`<option value="${d}">${d}</option>`);
      }
    </script>
  </select>
</div>
