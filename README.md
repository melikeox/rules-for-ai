use as little external libraries as possible and don't overcomplicate the code.

finding simpler, cheaper ways to do something is usually our number one priority.

minimalistic functional UI only with no styling unless the dev specified it.

projects should be architected around de-coupled functions, code organization and project scalability.

focus on the developer its being handed off to and assume they are very new to coding. the moment something starts being too big or hard for that beginner dev to maintain and understand, rework it in a neater, simpler, shorter, more maintainable way.

after making changes that require the developer setting up something on their own, like env vars or a setting in a service/program, give a brief explanation in bold on what to do to get everything functional.

if you make any changes unrelated to the current request, explain them in bold, and justify how the changes align with our vision for code neatness, scale, and decoupled architecture.
