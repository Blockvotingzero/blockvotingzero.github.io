<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nigeria Map Stats</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      margin: 20px;
      gap: 20px;
    }

    #map {
      width: 600px;
      height: auto;
    }

    #stats {
      flex: 1;
      min-width: 300px;
      border: 1px solid #ccc;
      border-radius: 5px;
      padding: 10px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }

    select {
      width: 100%;
      padding: 5px;
      margin-bottom: 10px;
    }

    table {
      width: 100%;
      border-collapse: collapse;
    }

    table, th, td {
      border: 1px solid #ddd;
    }

    th, td {
      padding: 8px;
      text-align: left;
    }

    th {
      background-color: #f4f4f4;
    }

    .state {
      fill: black;
      stroke: white;
      cursor: pointer;
    }

    .state:hover {
      fill: white;
      stroke: black;
    }

    @media (max-width: 768px) {
      .container {
        flex-direction: column;
      }

      #map {
        width: 100%;
      }
    }
  </style>
</head>
<body>
  <h1>Nigeria Election Stats</h1>
  <div class="container">
    <div id="map">
      <!-- SVG Map of Nigeria -->
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 600">
        <!-- Replace with the actual SVG paths for the states -->
        <g id="states">
          <path id="Lagos" class="state" d="M100,100 L150,100 L150,150 L100,150 Z" title="Lagos"></path>
          <path id="Kano" class="state" d="M200,100 L250,100 L250,150 L200,150 Z" title="Kano"></path>
          <path id="Abuja" class="state" d="M300,100 L350,100 L350,150 L300,150 Z" title="Abuja"></path>
          <!-- Add paths for all states -->
        </g>
      </svg>
    </div>
    <div id="stats">
      <select id="stateSelector">
        <option value="">Select a state</option>
        <option value="Lagos">Lagos</option>
        <option value="Kano">Kano</option>
        <option value="Abuja">Abuja</option>
        <!-- Add options for all states -->
      </select>
      <table>
        <thead>
          <tr>
            <th>Candidate</th>
            <th>Votes</th>
            <th>%</th>
          </tr>
        </thead>
        <tbody id="statsTable">
          <tr>
            <td>Bola Tinubu</td>
            <td>8,794,726</td>
            <td>36.61%</td>
          </tr>
          <tr>
            <td>Atiku Abubakar</td>
            <td>6,984,520</td>
            <td>29.07%</td>
          </tr>
          <tr>
            <td>Peter Obi</td>
            <td>6,101,533</td>
            <td>25.40%</td>
          </tr>
          <tr>
            <td>Rabiu Kwankwaso</td>
            <td>1,496,687</td>
            <td>6.23%</td>
          </tr>
          <tr>
            <td>Others</td>
            <td>648,474</td>
            <td>2.70%</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>

  <script>
    // Dummy stats for each state
    const stateStats = {
      Lagos: [
        { candidate: 'Bola Tinubu', votes: '1,500,000', percent: '40%' },
        { candidate: 'Atiku Abubakar', votes: '1,000,000', percent: '27%' },
        { candidate: 'Peter Obi', votes: '900,000', percent: '25%' },
        { candidate: 'Rabiu Kwankwaso', votes: '300,000', percent: '8%' }
      ],
      Kano: [
        { candidate: 'Bola Tinubu', votes: '2,000,000', percent: '50%' },
        { candidate: 'Atiku Abubakar', votes: '1,200,000', percent: '30%' },
        { candidate: 'Peter Obi', votes: '600,000', percent: '15%' },
        { candidate: 'Rabiu Kwankwaso', votes: '200,000', percent: '5%' }
      ],
      Abuja: [
        { candidate: 'Bola Tinubu', votes: '500,000', percent: '33%' },
        { candidate: 'Atiku Abubakar', votes: '400,000', percent: '26%' },
        { candidate: 'Peter Obi', votes: '600,000', percent: '39%' },
        { candidate: 'Rabiu Kwankwaso', votes: '50,000', percent: '2%' }
      ]
    };

    const statsTable = document.getElementById('statsTable');
    const stateSelector = document.getElementById('stateSelector');
    const states = document.querySelectorAll('.state');

    function updateStats(state) {
      const stats = stateStats[state] || stateStats['Lagos']; // Default to Lagos
      statsTable.innerHTML = stats.map(stat => `
        <tr>
          <td>${stat.candidate}</td>
          <td>${stat.votes}</td>
          <td>${stat.percent}</td>
        </tr>
      `).join('');
    }

    states.forEach(state => {
      state.addEventListener('click', () => {
        updateStats(state.id);
      });
    });

    stateSelector.addEventListener('change', (e) => {
      updateStats(e.target.value);
    });
  </script>
</body>
</html>
