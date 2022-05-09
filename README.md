# MilestoneAnniversaries

**Programming Assessment**

## Installation

Run `asdf install` to install the correct version of Erlang and Elixir (if you use it as a package manager)

Run `mix deps.get`

You can run the program in 2 ways:
  - By running the executable script `./shipping_validate`
  - By running with `iex -S mix`
      - while on `iex`, you can run the function `MilestoneAnniversaries.direct_report/2`  
      ```elixir
      iex> MilestoneAnniversaries.direct_report("employee_data.csv", "10/01/2015")
      ```
      This function accepts 2 arguments. The path to a csv file and a date in mm/dd/yyyy format


