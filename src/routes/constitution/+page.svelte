<script>
    import { dues } from '$lib/utils/helper';
    let one, oneOne, oneOneOne, oneTwo, oneTwoOne, oneTwoTwo, oneTwoThree, oneTwoFour, oneTwoFive, oneThree;
    let two, twoOne, twoTwo, twoThree;
    let three, threeOne;
    let four, fourOne, fourTwo;
    let five, fiveOne;
    let six, sixOne, sixTwo, sixThree;
    let seven, sevenOne, sevenTwo, sevenThree;

    const goToSection = (section) => {
        const top = section.getBoundingClientRect().top + window.pageYOffset;
        window.scrollTo({left: 0, top, behavior: 'smooth'});
    }
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The PiGGskin Perspective League Details</title>
    <style>
        body { font-family: Arial, sans-serif; line-height: 1.6; margin: 20px; }
        h1, h2, h3, h4, h5 { color: #2c3e50; }
        p { margin: 10px 0; }
        ul { margin: 10px 0 10px 20px; }
        li { margin: 5px 0; }
    </style>
</head>
<body>
    <h1>League Name: The PiGGskin Perspective</h1>
    <p><strong>League Host Site:</strong> Sleeper</p>
    <p><strong>League URL:</strong> <a href="https://sleeper.com/leagues/950431527228370944/" target="_blank">https://sleeper.com/leagues/950431527228370944/</a></p>
    
    <h2>Mission</h2>
    <p>We the Fantasy Football Managers of The PiGGskin Perspective Dynasty League aim to foster an environment that promotes fair play, healthy competition, and everlasting entertainment…</p>

    <h2>Values</h2>
    <ul>
        <li>Mutual Respect</li>
        <li>Ambition</li>
        <li>Yardstick for Fair Play</li>
        <li>Outstanding Sportsmanship</li>
        <li>Reliable Community</li>
        <li>Stress-Free and Positivity</li>
    </ul>

    <h2>League Structure</h2>
    <p><strong>Number of Teams:</strong> 12</p>
    <p><strong>Roster Size:</strong> 27 (11 Starters, 12 Bench, 4 Taxi Squad)</p>
    <p><strong>Starting Lineup:</strong> 1 QB, 3 RB, 3 WR, 1 TE, 2 FLX (W/R/T), SuperFlx (Q/W/R/T)</p>
    <p><strong>Scoring:</strong> See Sleeper on the app or website for comprehensive scoring settings</p>
    <p>Median scoring will be implemented (e.g., if a team scores higher than the median output of all teams in a given week, they will earn a win; regular matchup outcomes will still be counted)</p>

    <h2>League Fees</h2>
    <p><strong>Entry Fee:</strong> Initial Entry Fee- $75 ($50 for the current year and $25 down payment for the following year)</p>
    <p>After the initial year of the league, $50 will be due each year ($25 for the remainder of the current year and $25 for the down payment for the following year)</p>
    <p>All payments will be due via Venmo or Zelle</p>
    <p><strong>Payment Deadline:</strong> One week before the rookie draft (for year one, two weeks before the veteran draft)</p>
    <p>If payment is not submitted by the deadline, there will be consequences</p>

    <h2>Payouts</h2>
    <ul>
        <li>1st Place- $500</li>
        <li>2nd Place- $50</li>
        <li>Regular Season Champion- $50</li>
    </ul>

    <h2>Draft</h2>
    <h3>Rookie Draft</h3>
    <p>Linear, 4-round, slow draft, held approximately after the conclusion of the NFL Draft</p>
    <p>Each manager will have 4 hours to make each selection</p>
    <p>If a manager fails to make a selection within the allotted amount of time, they will receive the best available player</p>
    <p>The draft will automatically pause between 12:00 AM - 8:00 AM.</p>

    <h4>Picks 1-4 will be assigned based on a hybrid points system which will then be used as a part of a lottery system (combines regular season and postseason performance)</h4>
    <ul>
        <li>Regular Season Finish (4 times seed in consolation bracket)</li>
        <li>12th Place (4 Seed)- 16 points</li>
        <li>11th Place (3 Seed)- 12 points</li>
        <li>10th Place (2 Seed)- 8 points</li>
        <li>9th Place (1 Seed)- 4 points</li>
        <li>Consolation Bracket Finish</li>
        <li>Winner- 8 points</li>
        <li>Runner Up- 4 points</li>
        <li>3rd Place- 2 points</li>
        <li>4th Place- 1 point</li>
    </ul>
    <p>Any ties will be broken based on the worse seed</p>
    <p>Lottery Balls (based on the total number of points awarded) using <a href="https://www.fantasydraftlottery.com/" target="_blank">fantasydraftlottery.com</a></p>
    <ul>
        <li>1st- 50</li>
        <li>2nd- 30</li>
        <li>3rd- 15</li>
        <li>4th- 5</li>
    </ul>
    <p>Pick 5 will be automatically awarded to the 8th-place team from the regular season</p>
    <p>Pick 6 will be awarded to the worst seed remaining of the eliminated teams from the winner’s bracket</p>
    <p>Picks 7-11 will be based on how the winner’s consolation bracket games pan out (ex. In the 5th place game, the loser will be assigned the better pick)</p>
    <p>Pick 12 assigned to the previous season’s champion</p>
    <p>Both rookies and veterans (free agents) may be drafted</p>

    <h3>Startup Draft</h3>
    <p>The Inaugural Veteran Draft will consist of a 27-round snake draft with NO third-round reversal; includes ONLY veterans</p>
    <p>The draft is scheduled to begin on June 30th, 2023, at noon EDT</p>
    <p>The draft order is filled out with the help of a random order generator. However, the order gives managers the ability to pick where they can draft from (in either the veteran draft or the initial rookie draft)</p>
    <p>Managers will be allotted 8 hours to make each selection</p>
    <p>If a manager does not make a selection within the allotted amount of time, the best player available will automatically be added to their team</p>
    <p>The draft will automatically pause between 12:00 AM - 8:00 AM.</p>
    <h4>Draft Order (Year 2 Rookie Draft):</h4>
    <ul>
        <li>Ben Andrews</li>
        <li>Sam Decker</li>
        <li>Zach Esch</li>
        <li>Charles Walter</li>
        <li>Patrick & Karl Fink</li>
        <li>Jett Rosenstein</li>
        <li>Eric Tuan</li>
        <li>Brendan Lynch & Matt Maouad</li>
        <li>Mike Maerz</li>
        <li>Jacob Goldman</li>
        <li>Jared Doyle</li>
        <li>Tommy Fink</li>
    </ul>

    <h2>Trades</h2>
    <p><strong>Trade Deadline:</strong> A trade deadline will be in effect after the regular season</p>
    <p><strong>Trade Review:</strong> All trades will be reviewed by the co-commissioners. If there is no suspicion of collusion, the trade will be put through immediately. If there is enough evidence of collusion, the trade will be vetoed and both parties involved will be put on probation for the remainder of the season.</p>
    <p>Once the season ends, the league will vote on whether to renew the offending league members (a majority vote is needed to renew)</p>
    <p>League members can make trades for future picks (ex. 2024, 2025, etc.)</p>
    <p>League members should operate in good faith when making trades involving picks</p>

    <h2>Roster Management</h2>
    <h3>Waivers</h3>
    <p>$1000 FAAB (resets after the start of the new league year)</p>
    <p><strong>Minimum Bid:</strong> $1</p>
    <p>Players will stay on Waivers after games until 3:00 AM on Wednesday</p>
    <p>In the event of a tie (FAAB bids), the player will be awarded to the manager with the higher waiver priority (based on the reverse order of standings)</p>
    <p>In the offseason, the schedule will be modified. Waivers will be processed three days a week (Tuesday, Thursday, and Sunday) at noon ET. Once the league year starts (day after the NFL draft), waivers will process daily at noon ET</p>

    <h3>Taxi Squad</h3>
    <p>4 spots</p>
    <p>Players may be kept on the Taxi Squad for up to 3 years</p>
    <p>Once a player is promoted to the active roster, they cannot be moved back to the Taxi Squad</p>
    <p>The Taxi Squad will lock after the season concludes (i.e., cannot move players up and down to/from the Taxi Squad after the season is over)</p>

    <h2>Lineup Setting</h2>
    <p>Managers must set their lineups before the start of each player's game</p>
    <p>If a player is deemed out or on Injured Reserve, a league manager can manually substitute the player out of the starting lineup if the offending manager does not do so. This must be done before the start of the respective player’s game.</p>

    <h2>Playoffs</h2>
    <p>The top 6 teams (based on the regular season standings) will qualify for the playoffs</p>
    <p>Playoffs will occur from Weeks 15-17</p>
    <p>The top 2 seeds will receive a first-round bye (Week 15)</p>
    <p>The highest remaining seed after each round will play the lowest remaining seed</p>
    <p>The consolation bracket will also be in effect during the playoffs (Weeks 15-17)</p>
    <p><strong>Matchups:</strong></p>
    <ul>
        <li>Week 15: 3rd Seed vs. 6th Seed, 4th Seed vs. 5th Seed</li>
        <li>Week 16: 1st Seed vs. Lowest Remaining Seed, 2nd Seed vs. Highest Remaining Seed</li>
        <li>Week 17: Winners of Week 16</li>
    </ul>

    <h2>Expansion</h2>
    <p>If we expand the league from 12 to 14 teams, there will be a supplemental draft after the start-up draft (which will be the year after the initial start-up draft)</p>

    <h2>League Management</h2>
    <p>Jett Rosenstein and Tommy Fink will serve as co-commissioners</p>
    <p>The co-commissioners will handle day-to-day operations, maintain the integrity of the league, and ensure a smooth-running fantasy football experience for all managers</p>
    <p>The co-commissioners reserve the right to make executive decisions in the best interest of the league</p>
    <p>In the event that both co-commissioners are unavailable, a substitute commissioner will be appointed</p>

    <h2>Conduct and Integrity</h2>
    <p>All managers are expected to maintain the highest level of integrity and sportsmanship</p>
    <p>Collusion, cheating, or any form of unethical behavior will not be tolerated and will be met with severe consequences, including potential expulsion from the league</p>

    <h2>Disputes</h2>
    <p>All disputes will be resolved by the co-commissioners</p>
    <p>If a resolution cannot be reached, a league vote will be held</p>
    <p>The decision of the league vote will be final</p>

    <h2>Amendments</h2>
    <p>The league constitution may be amended by a majority vote of the league managers</p>
    <p>Any proposed amendments must be submitted in writing to the co-commissioners for consideration</p>

    <h2>Conclusion</h2>
    <p>We are committed to creating a fun, fair, and competitive fantasy football league. By joining The PiGGskin Perspective, you agree to abide by the rules and guidelines outlined in this constitution. Let's have a great season!</p>

    <p>-- Jett Rosenstein and Tommy Fink, Co-Commissioners</p>
</body>
</html>
