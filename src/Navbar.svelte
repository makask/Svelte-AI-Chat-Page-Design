<script>

</script>

<div class="navbar">
    <div>
        <p class="nav-title"><strong>CLOUDCHAT</strong>&nbsp;AI</p>
        <hr>
        <table>
            <tr>
                <th><i class="fa-solid fa-wand-magic-sparkles" style="color: #5d3aed;"></i></th>
                <th><a href="/"><strong>Chat UI</strong></a></th>
                <th></th>
            </tr>
        </table>
    
        <table>
            <tr>
              <th><i class="fa-regular fa-copy"></i></th>
              <th><a href="/"><strong>Other Pages</strong></a></th>
              <th></th>
            </tr>
            <tr>
                <td></td>
                <td><a href="/">Prompt Page</a></td>
                <td></td>
            </tr>
            <tr>
                <td></td>
                <td><a href="/">Register</a></td>
                <td></td>
            </tr>
            <tr>
                <td></td>
                <td><a href="/">Sign in</a></td>
                <td></td>
            </tr>
          </table>
    
          <table class="table-gray">
            <tr>
              <th><i class="fa-solid fa-lock"></i></th>
              <th><a href="/"><strong>Admin Pages</strong></a></th>
              <th><button class="btn-pro">PRO</button></th>
            </tr>
            <tr>
              <td></td>
              <td><a href="/">All Templates</a></td>
              <td></td>
            </tr>
            <tr>
              <td></td>
              <td><a href="/">New Templates</a></td>
              <td></td>
            </tr>
            <tr>
                <td></td>
                <td><a href="/">Edit Template</a></td>
                <td></td>
            </tr>
            <tr>
                <td></td>
                <td><a href="/">Users Overview</a></td>
                <td></td>
            </tr>
            <tr>
                <td></td>
                <td><a href="/">Sign in</a></td>
                <td></td>
            </tr>
          </table>
    </div>
    
      <div class="user-div">
          <img class="user-image" src="images/user.jpg" alt="userimage"/>
          <p><strong>Name Surname</strong></p>
          <button class="btn-logout"><i class="fa-solid fa-right-from-bracket"></i></button>
      </div>
</div>

<style>
    .navbar {
        display: flex;
        flex-direction: column;
        margin-left: 10px;
        min-height: 94vh;
        border-radius: 12px;
        box-shadow: 10px 0 20px 0 rgba(211, 211, 211, 0.5);
        padding: 10px;
        justify-content: space-between;
    }

    table {
        text-align: left;
    }

    .btn-pro{
        color: #8e74ff;
        background-color: #f2efff;
        border-radius: 12px;
        font-weight: bold;
        font-size: 12px;
        border:none;
        width: 50px;
    }

    .btn-logout{
        background-color: #ffffff;
        border: 1px solid lightgray;
        border-radius: 50%;
        padding: 12px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
    }

    .table-gray{
        opacity: 0.6;
    }

    .nav-title{
        margin-top: 40px;
        font-size: 26px;
    }

    table{
        font-size: 16px;
        margin-top: 30px;
    }

    .nav-title, table{
        margin-bottom: 10px;
    }
</style>