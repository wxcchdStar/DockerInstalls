FROM cptactionhank/atlassian-jira-software:7.4.0
ADD atlassian-extras-3.2.jar ${JIRA_INSTALL}/atlassian-jira/WEB-INF/lib/atlassian-extras-3.2.jar
ENTRYPOINT ["/docker-entrypoint.sh"]
CMD ["/opt/atlassian/jira/bin/start-jira.sh", "-fg"]