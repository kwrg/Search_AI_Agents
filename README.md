Description
----
This project involves using the CrewAI framework and the Serper API tool to create internet searching AI agents that gather laptop prices.

Python Libraries
----
import pandas as pd

import crewai

from crewai import Agent, Task, Crew, Process

import os

from crewai_tools import SerperDevTool

from crewai import LLM

from dotenv import load_dotenv

from crewai import Agent, Task, Crew, Process

from crewai_tools import SerperDevTool
